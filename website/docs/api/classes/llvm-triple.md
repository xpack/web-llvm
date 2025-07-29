---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/triple
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Triple` Class

<p><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> - Helper class for working with autoconf configuration names. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Triple { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ArchType { <a href="#a547abd13f7a3c063aa72c8192a868154">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">SubArchType { <a href="#a9ffca842bbaefcf99484f59a83b618d4">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">VendorType { <a href="#a96fe35195867c94aef1adf2ad0e20eec">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">OSType { <a href="#a3cfefc755ab656000934f91193afb1cd">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">EnvironmentType { <a href="#a1778f5c464f88710033f7e11e84a9324">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ObjectFormatType { <a href="#a83e907e55fa50e093caa96a0aff96201">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1743babb7e87104be8a0e357342e4a00">Data</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a547abd13f7a3c063aa72c8192a868154">ArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98033956d2c805e5654718668623d53d">Arch</a> {}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The parsed arch type. <a href="#a98033956d2c805e5654718668623d53d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9ffca842bbaefcf99484f59a83b618d4">SubArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad601895281985ce2950af09921eaca87">SubArch</a> {}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The parsed subarchitecture type. <a href="#ad601895281985ce2950af09921eaca87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a96fe35195867c94aef1adf2ad0e20eec">VendorType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abec3316862206317ea114d6eeffddc61">Vendor</a> {}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The parsed vendor type. <a href="#abec3316862206317ea114d6eeffddc61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3cfefc755ab656000934f91193afb1cd">OSType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfc30435951b5d0e9909f1a8bae62b4e">OS</a> {}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The parsed OS type. <a href="#acfc30435951b5d0e9909f1a8bae62b4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1778f5c464f88710033f7e11e84a9324">EnvironmentType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cbedbcd276055a53b0038221b131b7e">Environment</a> {}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The parsed Environment type. <a href="#a5cbedbcd276055a53b0038221b131b7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a83e907e55fa50e093caa96a0aff96201">ObjectFormatType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc57e811c09e0487d3a29bac39b62faf">ObjectFormat</a> {}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The object format type. <a href="#abc57e811c09e0487d3a29bac39b62faf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb80731bb9cdd5bbf4deaa30512dd327">getCanonicalVersionForOS</a> (OSType OSKind, const VersionTuple &amp;Version)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a canonicalized OS version number for the specified OS. <a href="#acb80731bb9cdd5bbf4deaa30512dd327">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Normalization Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CanonicalForm { <a href="#a1d5b377df30da16764880240c5c6b02e">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Canonical form. <a href="#a1d5b377df30da16764880240c5c6b02e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33c480b0848b82efb6835907a88e7b22">normalize</a> (CanonicalForm Form=CanonicalForm::ANY) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the normalized form of this triple's string. <a href="#a33c480b0848b82efb6835907a88e7b22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c2fb6bace55f9b58ed0ba9fe363299e">normalize</a> (StringRef Str, CanonicalForm Form=CanonicalForm::ANY)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turn an arbitrary machine specification into the canonical triple form (or something sensible that the <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> class understands if nothing better can reasonably be done). <a href="#a5c2fb6bace55f9b58ed0ba9fe363299e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15410866a30d89459a6f99034202e475">Triple</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor is the same as an empty string and leaves all triple fields unknown. <a href="#a15410866a30d89459a6f99034202e475">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5795a74557bb339afa955660ecb76247">Triple</a> (const Twine &amp;Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a triple from the string representation provided. <a href="#a5795a74557bb339afa955660ecb76247">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a8e516b5874b78eb8bc72e644d62ae5">Triple</a> (const Twine &amp;ArchStr, const Twine &amp;VendorStr, const Twine &amp;OSStr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a triple from string representations of the architecture, vendor, and OS. <a href="#a3a8e516b5874b78eb8bc72e644d62ae5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f144736db0877eaef0c6904afee0187">Triple</a> (const Twine &amp;ArchStr, const Twine &amp;VendorStr, const Twine &amp;OSStr, const Twine &amp;EnvironmentStr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a triple from string representations of the architecture, vendor, OS, and environment. <a href="#a2f144736db0877eaef0c6904afee0187">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2babdb16d78b57252b464a5c73d78f1">operator==</a> (const Triple &amp;Other) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae30aee607a7f1b0907b66becc29d5bd3">operator!=</a> (const Triple &amp;Other) const</td>
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

## Typed Component Access Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a547abd13f7a3c063aa72c8192a868154">ArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the parsed architecture type of this triple. <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9ffca842bbaefcf99484f59a83b618d4">SubArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f6aa922f9f6991e7d8aecb147e08fd4">getSubArch</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>get the parsed subarchitecture type for this triple. <a href="#a2f6aa922f9f6991e7d8aecb147e08fd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a96fe35195867c94aef1adf2ad0e20eec">VendorType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4d9af9c278219b313508fce336b7d83">getVendor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the parsed vendor type of this triple. <a href="#ab4d9af9c278219b313508fce336b7d83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3cfefc755ab656000934f91193afb1cd">OSType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the parsed operating system type of this triple. <a href="#a5a777de4cd152c5b22b9d28439326d50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee1760b5f339b38a6f711a2794cf0350">hasEnvironment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this triple have the optional environment (fourth) component? <a href="#aee1760b5f339b38a6f711a2794cf0350">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1778f5c464f88710033f7e11e84a9324">EnvironmentType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the parsed environment type of this triple. <a href="#a6beb910ab0112de8679b6d2703351384">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ad45f83c98f9639777cb9924cef58fd">getEnvironmentVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the version number from the OS name component of the triple, if present. <a href="#a5ad45f83c98f9639777cb9924cef58fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a83e907e55fa50e093caa96a0aff96201">ObjectFormatType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e265a0d332c3e2db0acf0c7afd4175d">getObjectFormat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the object format for this triple. <a href="#a2e265a0d332c3e2db0acf0c7afd4175d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a024faa768c9d7b624a68980113f92693">getOSVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the version number from the OS name component of the triple, if present. <a href="#a024faa768c9d7b624a68980113f92693">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6bb6cb4330e31951d06537d80c39e62">getOSMajorVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return just the major version number, this is specialized because it is a common query. <a href="#ae6bb6cb4330e31951d06537d80c39e62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0a7f9a135ee2e5c73cb076f6867ce8e">getMacOSXVersion</a> (VersionTuple &amp;Version) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the version number as with getOSVersion and then translate generic "darwin" versions to the corresponding OS X versions. <a href="#aa0a7f9a135ee2e5c73cb076f6867ce8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcf64addbfd5833e0c59117fee9bedec">getiOSVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the version number as with getOSVersion. <a href="#adcf64addbfd5833e0c59117fee9bedec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07060601788098311a70d6e43327cb08">getWatchOSVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the version number as with getOSVersion. <a href="#a07060601788098311a70d6e43327cb08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72667fa2e9534947a4794acf8958f884">getDriverKitVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the version number as with getOSVersion. <a href="#a72667fa2e9534947a4794acf8958f884">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e60a7cae0edfa1045ed0e35c9b55088">getVulkanVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the Vulkan version number from the OSVersion and SPIR-V version (SubArch). <a href="#a6e60a7cae0edfa1045ed0e35c9b55088">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ac5d7614594ccea16725535d111652a">getDXILVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the DXIL version number from the OSVersion and DXIL version (SubArch). <a href="#a6ac5d7614594ccea16725535d111652a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Direct Component Access Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ad662bdf0613457ae9b81b47f5555b7">str</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc9985614536143e793244dfb66028c">getTriple</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2d9e5a5c22d594a05d4feae337de252">getArchName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the architecture (first) component of the triple. <a href="#ad2d9e5a5c22d594a05d4feae337de252">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a062f684a024e13d7280e178c95668678">getVendorName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the vendor (second) component of the triple. <a href="#a062f684a024e13d7280e178c95668678">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a483bbccede7948c656b0bd339f39218f">getOSName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the operating system (third) component of the triple. <a href="#a483bbccede7948c656b0bd339f39218f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a685d4808dcb1ae5133120d64593d515b">getEnvironmentName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the optional environment (fourth) component of the triple, or "" if empty. <a href="#a685d4808dcb1ae5133120d64593d515b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e404426d1eac2b4c19c8986d9d46cb3">getOSAndEnvironmentName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the operating system and optional environment components as a single string (separated by a '-' if the environment component is present). <a href="#a9e404426d1eac2b4c19c8986d9d46cb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade97ab011dc19854c9886f2c6d8ecc66">getEnvironmentVersionString</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the version component of the environment component as a single string (the version after the environment). <a href="#ade97ab011dc19854c9886f2c6d8ecc66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Convenience Predicates Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a261b9412ba2231505fc5d6ffa7d3a01a">getArchPointerBitWidth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the pointer width of this architecture. <a href="#a261b9412ba2231505fc5d6ffa7d3a01a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a619b009238bd7e0a7bb68afe88f2d2fd">getTrampolineSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the trampoline size in bytes for this configuration. <a href="#a619b009238bd7e0a7bb68afe88f2d2fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e0d7431e635bbbf753602d214d89f0e">isArch64Bit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the architecture is 64-bit. <a href="#a9e0d7431e635bbbf753602d214d89f0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae11d6e273225164d9da0c6cad55e093d">isArch32Bit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the architecture is 32-bit. <a href="#ae11d6e273225164d9da0c6cad55e093d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb3675c020f17151a02604b14c8cdb77">isArch16Bit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the architecture is 16-bit. <a href="#adb3675c020f17151a02604b14c8cdb77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc7c65abde53e1e420cab20d84d49cbb">isOSVersionLT</a> (unsigned Major, unsigned Minor=0, unsigned Micro=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function for doing comparisons against version numbers included in the target triple. <a href="#abc7c65abde53e1e420cab20d84d49cbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fa1f16bd79509b687e8c593a048a225">isOSVersionLT</a> (const Triple &amp;Other) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0092ef6558c242caa4916fbd7fd8da34">isMacOSXVersionLT</a> (unsigned Major, unsigned Minor=0, unsigned Micro=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Comparison function for checking OS X version compatibility, which handles supporting skewed version numbering schemes used by the "darwin" triples. <a href="#a0092ef6558c242caa4916fbd7fd8da34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6a7d5d218ef0d2334fe24eaf997bbb6">isMacOSX</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this a Mac OS X triple. <a href="#aa6a7d5d218ef0d2334fe24eaf997bbb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac36bf25c234d956997781778c866808e">isiOS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this an iOS triple. <a href="#ac36bf25c234d956997781778c866808e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf440ac7b84052680788f233de6bcdb6">isTvOS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this an Apple tvOS triple. <a href="#abf440ac7b84052680788f233de6bcdb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2eddca981f187178a53969d88465b4c">isWatchOS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this an Apple watchOS triple. <a href="#ac2eddca981f187178a53969d88465b4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14aca434442ff741fa55e97ddccd15ed">isWatchABI</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaba295444f638da56e58010cf7fb091d">isXROS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this an Apple XROS triple. <a href="#aaba295444f638da56e58010cf7fb091d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f396e16b49f3277fc279f94a12d03a5">isDriverKit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this an Apple DriverKit triple. <a href="#a1f396e16b49f3277fc279f94a12d03a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b121909a2e76bd11b0673b0eeb58b25">isOSzOS</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adab4eb95e1944ffb12f0d9b349782d3b">isAppleMachO</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this an Apple <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> triple. <a href="#adab4eb95e1944ffb12f0d9b349782d3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6fdf9b428bc3d57837022121c155cbf">isOSDarwin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this a "Darwin" OS (macOS, iOS, tvOS, watchOS, XROS, or DriverKit). <a href="#ab6fdf9b428bc3d57837022121c155cbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a66d02819186762f85145d632f9f81f">isSimulatorEnvironment</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7328346f2f8d6b9d897608882bc7758">isMacCatalystEnvironment</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c3d390e73840644c0bf96d1933b3396">isTargetMachineMac</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true for targets that run on a macOS machine. <a href="#a0c3d390e73840644c0bf96d1933b3396">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d98f3cc4fe2adddfa98dc0dbee55bdb">isOSNetBSD</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e54a3851d12ab87ef42ebff942bac13">isOSOpenBSD</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa98a01c1d72fde0f87823d204dc98334">isOSFreeBSD</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae891092a64f3b737dcba557a8450587c">isOSFuchsia</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03aa5e23acb1aace7f2d2014cd3382ab">isOSDragonFly</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a565d07b44e55cbff02db88c1d5cf3cb1">isOSSolaris</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3d505c1a9bc7380a73561d84d063ca9">isOSIAMCU</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70cdd4fe5787c4383db8bbd21570f062">isOSUnknown</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9611bb364d25198d356aa20527fcffb">isGNUEnvironment</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af70af5dfe0ad906d51c7ca09d13a3e2e">isOSHaiku</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS is Haiku. <a href="#af70af5dfe0ad906d51c7ca09d13a3e2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b2f9ab09b41fed3ffeb43eda2533d8">isUEFI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS is UEFI. <a href="#a76b2f9ab09b41fed3ffeb43eda2533d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7736bfc4c1afef875ecf02f2a7701fe3">isOSWindows</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS is Windows. <a href="#a7736bfc4c1afef875ecf02f2a7701fe3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c38226b3063da1cb0bd1ce44a31b48f">isOSWindowsOrUEFI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS is Windows or UEFI. <a href="#a7c38226b3063da1cb0bd1ce44a31b48f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6d6a4d950ccaa3be4ca4ff2f2169090">isKnownWindowsMSVCEnvironment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the environment is MSVC. <a href="#af6d6a4d950ccaa3be4ca4ff2f2169090">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed5b9fcccfe88a419343c80064d44d74">isWindowsMSVCEnvironment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the environment could be MSVC. <a href="#aed5b9fcccfe88a419343c80064d44d74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0544a852d0033d3980285dbd1133ac6">isWindowsArm64EC</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aff54e7e4562b21d5762a6ca406f9f7">isWindowsCoreCLREnvironment</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdd0d3d27ef11fd6ad21da63c3979d77">isWindowsItaniumEnvironment</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0fd88c696cfbb5c2648fe705dcdef5c">isWindowsCygwinEnvironment</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a398f3f1f57fae295ca4ae75a3b56fa59">isWindowsGNUEnvironment</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a145fccafbd4d3bb9ff459092d5a5616b">isOSCygMing</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests for either Cygwin or MinGW OS. <a href="#a145fccafbd4d3bb9ff459092d5a5616b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a438b0136b755625f50ea227cc19e5ad9">isOSMSVCRT</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this a "Windows" OS targeting a "MSVCRT.dll" environment. <a href="#a438b0136b755625f50ea227cc19e5ad9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dd94ab3854e0421e795ce04ee3babf9">isOSNaCl</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS is NaCl (Native Client) <a href="#a0dd94ab3854e0421e795ce04ee3babf9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a898af817f450422b11443c35c99e64da">isOSLinux</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS is Linux. <a href="#a898af817f450422b11443c35c99e64da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57ba86412d0c09795efe03bd06b8dba1">isOSKFreeBSD</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS is kFreeBSD. <a href="#a57ba86412d0c09795efe03bd06b8dba1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26f50a368caaea38084bc9b40769ade1">isOSHurd</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS is Hurd. <a href="#a26f50a368caaea38084bc9b40769ade1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bcb02d757ae9d46b7720d607ce67d76">isOSWASI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS is WASI. <a href="#a1bcb02d757ae9d46b7720d607ce67d76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac044f740fee04796ffe5ba17fdc3fa0c">isOSEmscripten</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS is Emscripten. <a href="#ac044f740fee04796ffe5ba17fdc3fa0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac517c6287b37ff0764afbb97f2a56b51">isOSGlibc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS uses glibc. <a href="#ac517c6287b37ff0764afbb97f2a56b51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98cf8213993e03f8b57f294bd66cb40c">isOSAIX</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS is AIX. <a href="#a98cf8213993e03f8b57f294bd66cb40c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b1293b8705b0bd5ae5c783029399016">isOSSerenity</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea6d215256ae43bc9149bf41f2cc7694">isOSBinFormatELF</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS uses the <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> binary format. <a href="#aea6d215256ae43bc9149bf41f2cc7694">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6300d761fd69580d711fad99b934950a">isOSBinFormatCOFF</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS uses the <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> binary format. <a href="#a6300d761fd69580d711fad99b934950a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a388a623b8ab44f9d44d0525b548fcff8">isOSBinFormatGOFF</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS uses the <a href="/web-llvm/docs/api/namespaces/llvm/goff">GOFF</a> binary format. <a href="#a388a623b8ab44f9d44d0525b548fcff8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a444e46ff0a17a6c9480eb151bd42c9bc">isOSBinFormatMachO</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the environment is <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a>. <a href="#a444e46ff0a17a6c9480eb151bd42c9bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e1c6e3713e5c441d358239f9fac89a7">isOSBinFormatWasm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS uses the Wasm binary format. <a href="#a1e1c6e3713e5c441d358239f9fac89a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a804d3966ad6c4daafeb8a7ae31b8ae2d">isOSBinFormatXCOFF</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS uses the <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> binary format. <a href="#a804d3966ad6c4daafeb8a7ae31b8ae2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7df3ae0918bd700a9c8507e3b158e06f">isOSBinFormatDXContainer</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the OS uses the DXContainer binary format. <a href="#a7df3ae0918bd700a9c8507e3b158e06f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17cc069acf48bda2ac7451a56536cb0c">isPS4</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is the PS4 platform. <a href="#a17cc069acf48bda2ac7451a56536cb0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad76134ab5457867366f4ed43758bb8d6">isPS5</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is the PS5 platform. <a href="#ad76134ab5457867366f4ed43758bb8d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd9044b8fc48fe6073b88c278aa12d28">isPS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is the PS4 or PS5 platform. <a href="#acd9044b8fc48fe6073b88c278aa12d28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f3873f607a36e40241082727fef44db">isAndroid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is Android. <a href="#a3f3873f607a36e40241082727fef44db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b920f74d7ae331cfd2740a790de541">isAndroidVersionLT</a> (unsigned Major) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bbfb6d92b2d86cf613bc425e5446b00">isMusl</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the environment is musl-libc. <a href="#a7bbfb6d92b2d86cf613bc425e5446b00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b2d28c3c85d4b6b274d2d3efbe0afff">isOHOSFamily</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is OHOS LiteOS default enviroment is also OHOS, but omited on triple. <a href="#a6b2d28c3c85d4b6b274d2d3efbe0afff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad59e9ffe0d450e94f287c540ad043130">isOpenHOS</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96c0dd9835688584c4d9121e8be7704f">isOSLiteOS</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8167b32a55564d0d023cdc3bcd5b0b6">isDXIL</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is DXIL. <a href="#af8167b32a55564d0d023cdc3bcd5b0b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74c3ac300c06a2c491256534b99b08b9">isShaderModelOS</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a8e844d6b87311c662964dd8826358">isVulkanOS</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd88a4e5f804888b864374a454f6d13f">isShaderStageEnvironment</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c0737f9edc41d1a0ec4b5ec9a7e8b87">isSPIR</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is SPIR (32- or 64-bit). <a href="#a1c0737f9edc41d1a0ec4b5ec9a7e8b87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad77183da26fd51a168f2cedcd0df3561">isSPIRV</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is SPIR-V (32/64-bit/Logical). <a href="#ad77183da26fd51a168f2cedcd0df3561">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4deb097184b76d30b09cfeac681aba19">isSPIROrSPIRV</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba6fc3ce3bf1813201d150730c918d70">isSPIRVLogical</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is SPIR-V Logical. <a href="#aba6fc3ce3bf1813201d150730c918d70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9871d348bbc1e85bd1daacb428238707">isNVPTX</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is <a href="/web-llvm/docs/api/namespaces/llvm/nvptx">NVPTX</a> (32- or 64-bit). <a href="#a9871d348bbc1e85bd1daacb428238707">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92da6cf2a6b4ce43d5c5e4ef110511aa">isAMDGCN</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is AMDGCN. <a href="#a92da6cf2a6b4ce43d5c5e4ef110511aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9318bd992483581cc335e1a33782ea45">isAMDGPU</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17b2679f91f697a4ffe46b872152e25b">isThumb</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is Thumb (little and big endian). <a href="#a17b2679f91f697a4ffe46b872152e25b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a846115743c5cbbf80216168ad22f906c">isARM</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> (little and big endian). <a href="#a846115743c5cbbf80216168ad22f906c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38835c05d2e959d03033c304cd94a1b1">isTargetEHABICompatible</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target supports the EHABI exception handling standard. <a href="#a38835c05d2e959d03033c304cd94a1b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d80f3ca652a8b79e7553951b0cf2f43">isArmT32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is T32. <a href="#a0d80f3ca652a8b79e7553951b0cf2f43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8899fb0df47fe32a7e53cf7a054febe4">isArmMClass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is an M-class. <a href="#a8899fb0df47fe32a7e53cf7a054febe4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad953e410aea43848740978d9a6529a82">isAArch64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> (little and big endian). <a href="#ad953e410aea43848740978d9a6529a82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ec13d6660c3676bc8f76c8b7f14f3e8">isAArch64</a> (int PointerWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> and pointers are the size specified by <span class="doxyComputerOutput">PointerWidth</span>. <a href="#a2ec13d6660c3676bc8f76c8b7f14f3e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93994a01f6ca3fdd3daf286e2712a465">isLoongArch32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is 32-bit <a href="/web-llvm/docs/api/namespaces/llvm/loongarch">LoongArch</a>. <a href="#a93994a01f6ca3fdd3daf286e2712a465">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66a1a1858e17b6bcfcbbb1d5229d275e">isLoongArch64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is 64-bit <a href="/web-llvm/docs/api/namespaces/llvm/loongarch">LoongArch</a>. <a href="#a66a1a1858e17b6bcfcbbb1d5229d275e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd03ec8096e2f185d677c27da21f922d">isLoongArch</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is <a href="/web-llvm/docs/api/namespaces/llvm/loongarch">LoongArch</a> (32- and 64-bit). <a href="#afd03ec8096e2f185d677c27da21f922d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73717ef7418a714f20be268c55a2c19e">isMIPS32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is MIPS 32-bit (little and big endian). <a href="#a73717ef7418a714f20be268c55a2c19e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52f9355613c6f3388d5761349926d835">isMIPS64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is MIPS 64-bit (little and big endian). <a href="#a52f9355613c6f3388d5761349926d835">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3b16cb8cc0190f3513f6fee6145c63c">isMIPS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is MIPS (little and big endian, 32- or 64-bit). <a href="#ac3b16cb8cc0190f3513f6fee6145c63c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0338eabc8ab4dff6368bdfae6ec94cbc">isPPC</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is PowerPC (32- or 64-bit LE or BE). <a href="#a0338eabc8ab4dff6368bdfae6ec94cbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fbc3fe5e4f1e0f9515cfac36293b1c8">isPPC32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is 32-bit PowerPC (little and big endian). <a href="#a5fbc3fe5e4f1e0f9515cfac36293b1c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab61d338cbe7892ab484e97c9b0c8c8c9">isPPC64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is 64-bit PowerPC (little and big endian). <a href="#ab61d338cbe7892ab484e97c9b0c8c8c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ab21929777b807678f98c873cdd7c7c">isPPC64ELFv2ABI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target 64-bit PowerPC big endian ABI is ELFv2. <a href="#a1ab21929777b807678f98c873cdd7c7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae08707e2e2afe994828112fbe8a89817">isPPC32SecurePlt</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target 32-bit PowerPC uses Secure PLT. <a href="#ae08707e2e2afe994828112fbe8a89817">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a578c0e35b3e3ed8c73e610a0882a9d6a">isRISCV32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is 32-bit RISC-V. <a href="#a578c0e35b3e3ed8c73e610a0882a9d6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64b2600935100a4be30d8a364609e427">isRISCV64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is 64-bit RISC-V. <a href="#a64b2600935100a4be30d8a364609e427">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92c6b6260dedf314bf70156000628e80">isRISCV</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is RISC-V (32- and 64-bit). <a href="#a92c6b6260dedf314bf70156000628e80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a692addc79837dc704398400593123895">isSPARC32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is 32-bit SPARC (little and big endian). <a href="#a692addc79837dc704398400593123895">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0e575c51232ced86460d9ae83f96cbc">isSPARC64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is 64-bit SPARC (big endian). <a href="#aa0e575c51232ced86460d9ae83f96cbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab61318fe3bda34b9889b7c4293d091be">isSPARC</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is SPARC. <a href="#ab61318fe3bda34b9889b7c4293d091be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade08dbf7a3d70b46b55c4257b3a536de">isSystemZ</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is <a href="/web-llvm/docs/api/namespaces/llvm/systemz">SystemZ</a>. <a href="#ade08dbf7a3d70b46b55c4257b3a536de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31d94b95418472bb1179f7c130ad3667">isX86</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is x86 (32- or 64-bit). <a href="#a31d94b95418472bb1179f7c130ad3667">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeb095611dceaee172b9ab66a9f765ba">isVE</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is <a href="/web-llvm/docs/api/namespaces/llvm/ve">VE</a>. <a href="#afeb095611dceaee172b9ab66a9f765ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf7f07dbe7dd1f7edd291b75005280bb">isWasm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is wasm (32- and 64-bit). <a href="#acf7f07dbe7dd1f7edd291b75005280bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64f24694a89d710b9a7f59e1f2df0d12">isCSKY</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32dff8f6f7ea462f82443a33fdf1e4ac">isArm64e</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is the Apple "arm64e" <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> subarch. <a href="#a32dff8f6f7ea462f82443a33fdf1e4ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47bfd723026a27a754135ac44f10b9b8">isABIN32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a292887fa6b4aa078f520d5884dda7ad9">isX32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is X32. <a href="#a292887fa6b4aa078f520d5884dda7ad9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a291cf24ece30f33f071b7f62ee0b9ec1">isBPF</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target is eBPF. <a href="#a291cf24ece30f33f071b7f62ee0b9ec1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae09fbe778f8a1f090e6d3fb5175bdb4b">isTime64ABI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if the target forces 64-bit time_t on a 32-bit architecture. <a href="#ae09fbe778f8a1f090e6d3fb5175bdb4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a287017c7824dea2df018a3e237cf2b52">isHardFloatABI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if the target forces hardfloat. <a href="#a287017c7824dea2df018a3e237cf2b52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49a399e1ef632107f1a062a3d22f2118">supportsCOMDAT</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target supports comdat. <a href="#a49a399e1ef632107f1a062a3d22f2118">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade012f998cea3bc03f6da0b08d422e6c">hasDefaultEmulatedTLS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target uses emulated TLS as default. <a href="#ade012f998cea3bc03f6da0b08d422e6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f39ef170cc0043edb23a89216122e18">hasDefaultTLSDESC</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the target supports both general-dynamic and TLSDESC, and TLSDESC is enabled by default. <a href="#a3f39ef170cc0043edb23a89216122e18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a553e5eede76e94cc97f728aee36cec71">hasDefaultDataSections</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target uses -data-sections as default. <a href="#a553e5eede76e94cc97f728aee36cec71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab893338da73c247a9d4f09038f7f80fe">hasDLLImportExport</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if the environment supports dllimport/export annotations. <a href="#ab893338da73c247a9d4f09038f7f80fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac338ba44be9ddbf09201b91cc7718985">getArchPointerBitWidth</a> (llvm::Triple::ArchType Arch)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the pointer width of this architecture. <a href="#ac338ba44be9ddbf09201b91cc7718985">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Mutators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af70f4019638c4a7cccaaad403c25c048">setArch</a> (ArchType Kind, SubArchType SubArch=NoSubArch)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the architecture (first) component of the triple to a known type. <a href="#af70f4019638c4a7cccaaad403c25c048">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af96094469e937492a76dd8e01e81e7cc">setVendor</a> (VendorType Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the vendor (second) component of the triple to a known type. <a href="#af96094469e937492a76dd8e01e81e7cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadd45e5c167eb85f1741ee869ea790e8">setOS</a> (OSType Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the operating system (third) component of the triple to a known type. <a href="#aadd45e5c167eb85f1741ee869ea790e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a472091dc314efebea60a6c5cff416cc9">setEnvironment</a> (EnvironmentType Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the environment (fourth) component of the triple to a known type. <a href="#a472091dc314efebea60a6c5cff416cc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e2cea374a7428eb1b5ec87ef774e552">setObjectFormat</a> (ObjectFormatType Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the object file format. <a href="#a0e2cea374a7428eb1b5ec87ef774e552">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58ffeec08324cdbd301158e5ef874cc3">setTriple</a> (const Twine &amp;Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set all components to the new triple <span class="doxyComputerOutput">Str</span>. <a href="#a58ffeec08324cdbd301158e5ef874cc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a096c1f8d7977e175075e210101627e0b">setArchName</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the architecture (first) component of the triple by name. <a href="#a096c1f8d7977e175075e210101627e0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a48b7e3794824f1fa399052765074ff">setVendorName</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the vendor (second) component of the triple by name. <a href="#a3a48b7e3794824f1fa399052765074ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3500e69a89f930107cd6f067371da4a">setOSName</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the operating system (third) component of the triple by name. <a href="#ab3500e69a89f930107cd6f067371da4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac154976a48deecf23babdeb1be05d9f">setEnvironmentName</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the optional environment (fourth) component of the triple by name. <a href="#aac154976a48deecf23babdeb1be05d9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eaa25de6a989d7332fa6044b3707226">setOSAndEnvironmentName</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the operating system and optional environment components with a single string. <a href="#a3eaa25de6a989d7332fa6044b3707226">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Helpers to build variants of a particular triple. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">llvm::Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13e7af62cc56f460209e36190829d78c">get32BitArchVariant</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Form a triple with a 32-bit variant of the current architecture. <a href="#a13e7af62cc56f460209e36190829d78c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">llvm::Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a424c4dc4d08741fa4615cc0c4ec956bd">get64BitArchVariant</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Form a triple with a 64-bit variant of the current architecture. <a href="#a424c4dc4d08741fa4615cc0c4ec956bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">llvm::Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb7bb8c037a9662d31b148af4efa2a5a">getBigEndianArchVariant</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Form a triple with a big endian variant of the current architecture. <a href="#adb7bb8c037a9662d31b148af4efa2a5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">llvm::Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a269e50214be37e2963f53f94518a1894">getLittleEndianArchVariant</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Form a triple with a little endian variant of the current architecture. <a href="#a269e50214be37e2963f53f94518a1894">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45678567c4d2b54e70800daa41897207">isLittleEndian</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether the target triple is little endian. <a href="#a45678567c4d2b54e70800daa41897207">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae86f9f850769a4896b883b0da1322a51">isCompatibleWith</a> (const Triple &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether target triples are compatible. <a href="#ae86f9f850769a4896b883b0da1322a51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8605d2bf7adf880652f2a4fe11ca050d">merge</a> (const Triple &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge target triples. <a href="#a8605d2bf7adf880652f2a4fe11ca050d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b7155e7913c06217d85f6a7a3250315">getMinimumSupportedOSVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some platforms have different minimum supported OS versions that varies by the architecture specified in the triple. <a href="#a9b7155e7913c06217d85f6a7a3250315">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Static helpers for IDs. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c78e5759f86ae499cd06dfc747464a9">getArchTypeName</a> (ArchType Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the canonical name for the <span class="doxyComputerOutput">Kind</span> architecture. <a href="#a7c78e5759f86ae499cd06dfc747464a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19adff7744a0fe75c2c083e6d9b710e1">getArchName</a> (ArchType Kind, SubArchType SubArch=NoSubArch)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the architecture name based on <span class="doxyComputerOutput">Kind</span> and <span class="doxyComputerOutput">SubArch</span>. <a href="#a19adff7744a0fe75c2c083e6d9b710e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6f1d6df1b516f446668f876f6c37b29">getArchTypePrefix</a> (ArchType Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the "prefix" canonical name for the <span class="doxyComputerOutput">Kind</span> architecture. <a href="#af6f1d6df1b516f446668f876f6c37b29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a298fc373d25fb899e8963abf7f88e2e0">getVendorTypeName</a> (VendorType Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the canonical name for the <span class="doxyComputerOutput">Kind</span> vendor. <a href="#a298fc373d25fb899e8963abf7f88e2e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8192d4072e4aaba803248250d1faf61c">getOSTypeName</a> (OSType Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the canonical name for the <span class="doxyComputerOutput">Kind</span> operating system. <a href="#a8192d4072e4aaba803248250d1faf61c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb703efa7aa5bddf5875fe8f2517e787">getEnvironmentTypeName</a> (EnvironmentType Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the canonical name for the <span class="doxyComputerOutput">Kind</span> environment. <a href="#abb703efa7aa5bddf5875fe8f2517e787">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada671e44e91b68a18f8a61f12dd1f475">getObjectFormatTypeName</a> (ObjectFormatType ObjectFormat)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name for the <span class="doxyComputerOutput">Object</span> format. <a href="#ada671e44e91b68a18f8a61f12dd1f475">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Static helpers for converting alternate architecture names. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a547abd13f7a3c063aa72c8192a868154">ArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d5efe3bb966ce825560b2e6dd46f8ec">getArchTypeForLLVMName</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The canonical type for the given LLVM architecture name (e.g., "x86"). <a href="#a5d5efe3bb966ce825560b2e6dd46f8ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> - Helper class for working with autoconf configuration names.</p>


<p>For historical reasons, we also call these 'triples' (they used to contain exactly three fields).</p>


<p>Configuration names are strings in the canonical form: ARCHITECTURE-VENDOR-OPERATING_SYSTEM or ARCHITECTURE-VENDOR-OPERATING_SYSTEM-ENVIRONMENT</p>


<p>This class is used for clients which want to support arbitrary configuration names, but also want to implement certain special behavior for particular configurations. This class isolates the mapping from the components of the configuration name to well known IDs.</p>


<p>At its core the <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> class is designed to be a wrapper for a triple string; the constructor does not change or normalize the triple string. Clients that need to handle the non-canonical triples that users often specify should use the normalize method.</p>


<p>See autoconf/config.guess for a glimpse into what configuration names look like in practice.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ArchType {#a547abd13f7a3c063aa72c8192a868154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Triple::ArchType </td>
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
<td class="doxyEnumItemName">UnknownArch<a id="a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">arm<a id="a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">armeb<a id="a547abd13f7a3c063aa72c8192a868154af65ab1964be676bea302940a45765021"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">aarch64<a id="a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">aarch64_be<a id="a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">aarch64_32<a id="a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">arc<a id="a547abd13f7a3c063aa72c8192a868154aed5f38c6bd089f09c02aae8072ceb514"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">avr<a id="a547abd13f7a3c063aa72c8192a868154a9b780628857be980e628bf44ae7dce56"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">bpfel<a id="a547abd13f7a3c063aa72c8192a868154a83d003d0efa0cd997646dc0343d7093f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">bpfeb<a id="a547abd13f7a3c063aa72c8192a868154abccdd747b05d7cfff6ae937ffdf5ba03"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">csky<a id="a547abd13f7a3c063aa72c8192a868154a21a4eb647191d4bd084ffdd749dd9100"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">dxil<a id="a547abd13f7a3c063aa72c8192a868154a9ca957896440ddfeeedda9c05723c150"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">hexagon<a id="a547abd13f7a3c063aa72c8192a868154a5770b66a2436004885ac116a8ac357d5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">loongarch32<a id="a547abd13f7a3c063aa72c8192a868154a0c64155961d19dceb44b43f5a9992d1a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">loongarch64<a id="a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">m68k<a id="a547abd13f7a3c063aa72c8192a868154ae3dbf1f961e0618ea793bc9c099b932a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">mips<a id="a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">mipsel<a id="a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">mips64<a id="a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">mips64el<a id="a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">msp430<a id="a547abd13f7a3c063aa72c8192a868154a752f0f4d07cf7dcdbe539a95dfe4cbff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ppc<a id="a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ppcle<a id="a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ppc64<a id="a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ppc64le<a id="a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">r600<a id="a547abd13f7a3c063aa72c8192a868154a060ea888d89f5d59a5743118e429296f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">amdgcn<a id="a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">riscv32<a id="a547abd13f7a3c063aa72c8192a868154ae84559483d0c0f2bddc802ce6f76dd8b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">riscv64<a id="a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">sparc<a id="a547abd13f7a3c063aa72c8192a868154a9ebafd1adc05a751215ae959f2891752"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">sparcv9<a id="a547abd13f7a3c063aa72c8192a868154a34e8fe940082d534b3957f06616c8227"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">sparcel<a id="a547abd13f7a3c063aa72c8192a868154a069fe14c1b6db6a31124817f2e57c954"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">systemz<a id="a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">tce<a id="a547abd13f7a3c063aa72c8192a868154ad7837c42372169017a6e5ff3eaa42d1d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">tcele<a id="a547abd13f7a3c063aa72c8192a868154a8f07c386f3b82ef15a54318946248f96"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">thumb<a id="a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">thumbeb<a id="a547abd13f7a3c063aa72c8192a868154a038a23cbd1756bf797c083c48229dcfd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">x86<a id="a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">x86_64<a id="a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">xcore<a id="a547abd13f7a3c063aa72c8192a868154a1e3f00d3a8c8c59f0f95fd80f1d3ba53"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">xtensa<a id="a547abd13f7a3c063aa72c8192a868154ab9cc677b26266a0658a4f6feb4ee0bdc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">nvptx<a id="a547abd13f7a3c063aa72c8192a868154ae06ff88d5da98b63a6b4397fcb7a6050"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">nvptx64<a id="a547abd13f7a3c063aa72c8192a868154a92ac53f0fca7e6c3f4e56a2d4903b9ae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">amdil<a id="a547abd13f7a3c063aa72c8192a868154a5ea1b051c09d0127f2d90e0ad6b487df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">amdil64<a id="a547abd13f7a3c063aa72c8192a868154ade794c636782fc46854cb047c40c164b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">hsail<a id="a547abd13f7a3c063aa72c8192a868154aca408a723390395eeaa343d8f1e307c4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">hsail64<a id="a547abd13f7a3c063aa72c8192a868154a74533b62667da81390b35d2a47709458"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">spir<a id="a547abd13f7a3c063aa72c8192a868154a475e7f13c36b181edba29cfcca212def"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">spir64<a id="a547abd13f7a3c063aa72c8192a868154a5973589725994222a16112b960c74323"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">spirv<a id="a547abd13f7a3c063aa72c8192a868154aeee38b63a639e89548c0efc74cab3b65"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">spirv32<a id="a547abd13f7a3c063aa72c8192a868154afc429c7efea3699ead2afe26b7db09df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">spirv64<a id="a547abd13f7a3c063aa72c8192a868154ae0a08d9852914cec82b405e32e87fbdc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">kalimba<a id="a547abd13f7a3c063aa72c8192a868154a5c48161b8fa1243dfab0169510c72bb1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">shave<a id="a547abd13f7a3c063aa72c8192a868154a396b3f1df93fc8cb904b66759a0d1a96"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">lanai<a id="a547abd13f7a3c063aa72c8192a868154a8ccdc49befcb57d683a4ed2025a7f60d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">wasm32<a id="a547abd13f7a3c063aa72c8192a868154ac0478f40eaacc5f340e93827756e7a33"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">wasm64<a id="a547abd13f7a3c063aa72c8192a868154ad6b7ed7027706d2960e771c6374025b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">renderscript32<a id="a547abd13f7a3c063aa72c8192a868154a863d4793e08f6a5a3ca20149b3e7a85d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">renderscript64<a id="a547abd13f7a3c063aa72c8192a868154a1c43e5f860c9e21dab6fcfc65f93945d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ve<a id="a547abd13f7a3c063aa72c8192a868154a419abb6aa1b60e8d534b06311c1e553c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastArchType<a id="a547abd13f7a3c063aa72c8192a868154a1a5e13493e6ef2f36af87aa2b2861d5a"></a></td>
<td class="doxyEnumItemDescription"> (= ve)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>

</div>
</div>

### EnvironmentType {#a1778f5c464f88710033f7e11e84a9324}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Triple::EnvironmentType </td>
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
<td class="doxyEnumItemName">UnknownEnvironment<a id="a1778f5c464f88710033f7e11e84a9324a6c32bcd90dff79307baf3147697ae1d3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GNU<a id="a1778f5c464f88710033f7e11e84a9324ae6c91532448c0be7978cf1bfcdaa11bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GNUT64<a id="a1778f5c464f88710033f7e11e84a9324a648404ce7e68eb5d5a6c60afa8744438"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GNUABIN32<a id="a1778f5c464f88710033f7e11e84a9324a75fa362b8315ce952fde83ff09a4c599"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GNUABI64<a id="a1778f5c464f88710033f7e11e84a9324a21e1198b41cc86aafe10fcd5a6ca330b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GNUEABI<a id="a1778f5c464f88710033f7e11e84a9324a73b4a675dd734e1efcab33de0d217a37"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GNUEABIT64<a id="a1778f5c464f88710033f7e11e84a9324a2343e70ca8369c9a61e3e25aa4e08216"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GNUEABIHF<a id="a1778f5c464f88710033f7e11e84a9324a699fcd7db202863a2a82143681dadb85"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GNUEABIHFT64<a id="a1778f5c464f88710033f7e11e84a9324ae5c77cfc976654fac7f3f50ee1352a8e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GNUF32<a id="a1778f5c464f88710033f7e11e84a9324a61ce851e1f60ad25421987629f5ac2c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GNUF64<a id="a1778f5c464f88710033f7e11e84a9324a587bfd81081ee91855e23c7cc05d4487"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GNUSF<a id="a1778f5c464f88710033f7e11e84a9324a9953bc1a6bb23d4a733faf9afb0df99a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GNUX32<a id="a1778f5c464f88710033f7e11e84a9324ab0c4c38b98e3b1482fc1c5afc8649e28"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GNUILP32<a id="a1778f5c464f88710033f7e11e84a9324a0a05a130bb4b1c97244ff98d64e0de5d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CODE16<a id="a1778f5c464f88710033f7e11e84a9324ace5d58a24effb264483f4af8b79b97b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EABI<a id="a1778f5c464f88710033f7e11e84a9324a847a953f3f994ab5453f075cea9ca7af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EABIHF<a id="a1778f5c464f88710033f7e11e84a9324af2b02c10c51141fdaa4cb49402e20169"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Android<a id="a1778f5c464f88710033f7e11e84a9324a0ceb06180ab5fc86e9ad27563b538439"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Musl<a id="a1778f5c464f88710033f7e11e84a9324a332336ad935952ff734309ce432de6d1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MuslABIN32<a id="a1778f5c464f88710033f7e11e84a9324a07818ec9990bfc4675291f2235ab6e8b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MuslABI64<a id="a1778f5c464f88710033f7e11e84a9324a27355a1eadfe9594a7acc5634d54bfc8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MuslEABI<a id="a1778f5c464f88710033f7e11e84a9324a8a7dd3fc84b97dc5b1a677d60e46df80"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MuslEABIHF<a id="a1778f5c464f88710033f7e11e84a9324ab711c5b8f1cd078c75864af125d07fef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MuslF32<a id="a1778f5c464f88710033f7e11e84a9324a66008454cd4031dad58b64c0eae7f9e4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MuslSF<a id="a1778f5c464f88710033f7e11e84a9324aff5daa73e757da85e8803ea0e323d5b0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MuslX32<a id="a1778f5c464f88710033f7e11e84a9324ae2e0845b94acce4ef8966096195201dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVM<a id="a1778f5c464f88710033f7e11e84a9324a40176fd51bd652566e1d48b5455fd081"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MSVC<a id="a1778f5c464f88710033f7e11e84a9324a6d53dbdf9a8b9b1092558cf23f83a95a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Itanium<a id="a1778f5c464f88710033f7e11e84a9324aa97aa42b85b1502e458177c354ab6788"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Cygnus<a id="a1778f5c464f88710033f7e11e84a9324a0521408131ca98c3ee4f486df216ea39"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CoreCLR<a id="a1778f5c464f88710033f7e11e84a9324afcb832e2cb16856e53500d3c1e52a890"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Simulator<a id="a1778f5c464f88710033f7e11e84a9324a587146bd8be66f0980d55ca2664c5642"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MacABI<a id="a1778f5c464f88710033f7e11e84a9324a0a522a127e133d8cd07fa678e6672695"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pixel<a id="a1778f5c464f88710033f7e11e84a9324a4bd403d91c4535171833f92e0ce36137"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Vertex<a id="a1778f5c464f88710033f7e11e84a9324a71b983b2a1bf8a46c5ac7d21de26fb4a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Geometry<a id="a1778f5c464f88710033f7e11e84a9324ade3aad57a34a47654ebeee1a2d4ab960"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Hull<a id="a1778f5c464f88710033f7e11e84a9324ac8bc9b9934c75b722dcdde3b705c0a51"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Domain<a id="a1778f5c464f88710033f7e11e84a9324a9250a1f506b7407b838bf0b494f9cd33"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Compute<a id="a1778f5c464f88710033f7e11e84a9324a35a7d7865588f76c4f300fb1f07ee1bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Library<a id="a1778f5c464f88710033f7e11e84a9324a38ed328b8551b06c5a133e54867110bf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RayGeneration<a id="a1778f5c464f88710033f7e11e84a9324a15bc4c083c1cda54e3011297b4bf8351"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Intersection<a id="a1778f5c464f88710033f7e11e84a9324ac5ff0a8f8e278b84cdd8518a6e0c67d8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AnyHit<a id="a1778f5c464f88710033f7e11e84a9324ab73388cc76387a636177ac9e405d0b39"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ClosestHit<a id="a1778f5c464f88710033f7e11e84a9324a783d818fcc0a9d1e095674aa7b255082"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Miss<a id="a1778f5c464f88710033f7e11e84a9324ad6c99823a0c7477c6412728485bb0fe7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Callable<a id="a1778f5c464f88710033f7e11e84a9324adf4a58c1d4eb1aeba280a3fc580e9f8d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mesh<a id="a1778f5c464f88710033f7e11e84a9324aa1a97c079fbb80fcd9ab0f5fa24f3025"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Amplification<a id="a1778f5c464f88710033f7e11e84a9324ab926bec66aeb0288525973f203bcb94a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpenCL<a id="a1778f5c464f88710033f7e11e84a9324a8a0496f998fd9139553edc0ef61c2cc4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpenHOS<a id="a1778f5c464f88710033f7e11e84a9324a582eb6a495698055109b21d02b959c2e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PAuthTest<a id="a1778f5c464f88710033f7e11e84a9324a74151519e4fd7f222963d600ad2d44b5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastEnvironmentType<a id="a1778f5c464f88710033f7e11e84a9324a3f86e726c47444861bcfd28023c3343c"></a></td>
<td class="doxyEnumItemDescription"> (= PAuthTest)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>

</div>
</div>

### ObjectFormatType {#a83e907e55fa50e093caa96a0aff96201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Triple::ObjectFormatType </td>
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
<td class="doxyEnumItemName">UnknownObjectFormat<a id="a83e907e55fa50e093caa96a0aff96201af2f88d8b470958614a01866d4714b5a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COFF<a id="a83e907e55fa50e093caa96a0aff96201aa943abc041caa1cc4c074bbf38b76267"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DXContainer<a id="a83e907e55fa50e093caa96a0aff96201a382f97aab858a35311f657a88f998a68"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELF<a id="a83e907e55fa50e093caa96a0aff96201a456b64e26b8bcdbd8294689615d8a055"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GOFF<a id="a83e907e55fa50e093caa96a0aff96201a7d71851eea2209e547ae06c9c03768f5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachO<a id="a83e907e55fa50e093caa96a0aff96201a2ed78f59e2d35011e1d1ed0ad96cf411"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPIRV<a id="a83e907e55fa50e093caa96a0aff96201ae057411e10951f5a7dc545e6199c5490"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Wasm<a id="a83e907e55fa50e093caa96a0aff96201a660d4029da29691e97daf8c8aabb1ffb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XCOFF<a id="a83e907e55fa50e093caa96a0aff96201a1f7d761ca747e66d2ac0caa0d54b1824"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>

</div>
</div>

### OSType {#a3cfefc755ab656000934f91193afb1cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Triple::OSType </td>
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
<td class="doxyEnumItemName">UnknownOS<a id="a3cfefc755ab656000934f91193afb1cda4b110a50637320a1a0db33999b809ddd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Darwin<a id="a3cfefc755ab656000934f91193afb1cda0824a8c56de913d60c6f55edc0ac3148"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DragonFly<a id="a3cfefc755ab656000934f91193afb1cda0e7175bb9a8eea9efd2a5e50b6ca84ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FreeBSD<a id="a3cfefc755ab656000934f91193afb1cda64fc6929b84f845ced55d3313ebcf423"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Fuchsia<a id="a3cfefc755ab656000934f91193afb1cdaad44ff9454db9e8eb2e38d964f0345b7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IOS<a id="a3cfefc755ab656000934f91193afb1cdafad6e6763679be1478d9283a7344d243"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KFreeBSD<a id="a3cfefc755ab656000934f91193afb1cda6506444610ddf1a927cf919508b2ea1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Linux<a id="a3cfefc755ab656000934f91193afb1cda76d4dd8dc67e3a11d975743f6d63a9df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lv2<a id="a3cfefc755ab656000934f91193afb1cda379ed41d00eaa4c446cdefc892d8762f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MacOSX<a id="a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NetBSD<a id="a3cfefc755ab656000934f91193afb1cdad10d236fcf52bdbf36bd6b401ca9e427"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpenBSD<a id="a3cfefc755ab656000934f91193afb1cda13c01bda5d01cb2264a0cebe7b411c54"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Solaris<a id="a3cfefc755ab656000934f91193afb1cdac44628c2fbd9505dc608a330838fccce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UEFI<a id="a3cfefc755ab656000934f91193afb1cda7af47f8e02ca8bd701e40ba03b2bcd95"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Win32<a id="a3cfefc755ab656000934f91193afb1cdafd0c0a465dca43ad44f79806a226a1ae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZOS<a id="a3cfefc755ab656000934f91193afb1cdafd36ac5f07b0474e2b5c167ab7158538"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Haiku<a id="a3cfefc755ab656000934f91193afb1cda55732429424dd801e57c7c667a8d4217"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RTEMS<a id="a3cfefc755ab656000934f91193afb1cda638da1f392b8b391c2af80e9d461d17b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NaCl<a id="a3cfefc755ab656000934f91193afb1cdaae17c480f3a0e37421e04400dca90d1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AIX<a id="a3cfefc755ab656000934f91193afb1cda55c9e8cff2a0eab89d1b234d419ee93f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CUDA<a id="a3cfefc755ab656000934f91193afb1cdac81124e2bdd6fb0d7b3fc4bd30233928"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NVCL<a id="a3cfefc755ab656000934f91193afb1cda6f69427cfc546c2402cdbee116ca6af9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMDHSA<a id="a3cfefc755ab656000934f91193afb1cda0a0dddcf03f8f66f7c13558b3c81d845"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PS4<a id="a3cfefc755ab656000934f91193afb1cda63d6dc93c7b6ab41ba169620a639bec1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PS5<a id="a3cfefc755ab656000934f91193afb1cda683700aa7afbff16fe3885d5ad05923c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFIAMCU<a id="a3cfefc755ab656000934f91193afb1cdaea39dbcca2c32c044d958aceb371bb13"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TvOS<a id="a3cfefc755ab656000934f91193afb1cda2838cf6df0f09591c50d752d46c4350d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WatchOS<a id="a3cfefc755ab656000934f91193afb1cda87a3c8454473c64f6d605ebd757759ad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BridgeOS<a id="a3cfefc755ab656000934f91193afb1cdac1302c2bd5aa5a28b3558b748e57e6ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DriverKit<a id="a3cfefc755ab656000934f91193afb1cda600aa0b72f321a0cdf0e4b3f38b9b6c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XROS<a id="a3cfefc755ab656000934f91193afb1cdabb5225659a201976ce2594df579e3623"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mesa3D<a id="a3cfefc755ab656000934f91193afb1cda81cc47a265b37fea8b5b3575b67ea6ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMDPAL<a id="a3cfefc755ab656000934f91193afb1cda7d8eb2c700c876375f588d68dc692f15"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HermitCore<a id="a3cfefc755ab656000934f91193afb1cda5523c4eadf302b516ae738ddf52076a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Hurd<a id="a3cfefc755ab656000934f91193afb1cdaf17d175b40b8e7ceedc92aea3929eb27"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASI<a id="a3cfefc755ab656000934f91193afb1cdab4b12e4f268dff8ead7f9194ee8da04b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Emscripten<a id="a3cfefc755ab656000934f91193afb1cdae7c70b9eb6106c04f131eca1e3be44ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ShaderModel<a id="a3cfefc755ab656000934f91193afb1cdac4081e09efdc53c28fc78e5ca68ea70a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LiteOS<a id="a3cfefc755ab656000934f91193afb1cdaf7d25a9254177b6890fd8c115503014d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Serenity<a id="a3cfefc755ab656000934f91193afb1cda3abcbc3caa438ea915121cdf3d373aae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Vulkan<a id="a3cfefc755ab656000934f91193afb1cda844b53b7eb8188bdea24d4147b10d2b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastOSType<a id="a3cfefc755ab656000934f91193afb1cda501b168d51e141389c4ab49481c49dc7"></a></td>
<td class="doxyEnumItemDescription"> (= Vulkan)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>

</div>
</div>

### SubArchType {#a9ffca842bbaefcf99484f59a83b618d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Triple::SubArchType </td>
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
<td class="doxyEnumItemName">NoSubArch<a id="a9ffca842bbaefcf99484f59a83b618d4a023f1e73b058ea58dba15516382eed52"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v9_6a<a id="a9ffca842bbaefcf99484f59a83b618d4a110b3a4de8e1b2d76335c6eb299a22f9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v9_5a<a id="a9ffca842bbaefcf99484f59a83b618d4a730333b03ef48149676803658abe7196"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v9_4a<a id="a9ffca842bbaefcf99484f59a83b618d4ad5841034e27eba09d31d90905cc0974b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v9_3a<a id="a9ffca842bbaefcf99484f59a83b618d4adde68b7158745bbd00b1320768e2ca23"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v9_2a<a id="a9ffca842bbaefcf99484f59a83b618d4a50198e2c009206d54f69a1ed6f457fe3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v9_1a<a id="a9ffca842bbaefcf99484f59a83b618d4a185d6eb97a379483b3c3a4284cd45cc2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v9<a id="a9ffca842bbaefcf99484f59a83b618d4ae60c9fe88a53cb6def09bc5b5137fe8d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v8_9a<a id="a9ffca842bbaefcf99484f59a83b618d4aaf8f8301b1acd585a755ca14ab6e333b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v8_8a<a id="a9ffca842bbaefcf99484f59a83b618d4a78ec4bc30363cbd6e87200a8b55340e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v8_7a<a id="a9ffca842bbaefcf99484f59a83b618d4a40920b0d5d8769714a371fcf155602f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v8_6a<a id="a9ffca842bbaefcf99484f59a83b618d4ac6acea60433ffb675553d7e1b5be256e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v8_5a<a id="a9ffca842bbaefcf99484f59a83b618d4ad98b7c5865d2b36266806520861920ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v8_4a<a id="a9ffca842bbaefcf99484f59a83b618d4aa61c5037a2303b17579ddecb3b9e224e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v8_3a<a id="a9ffca842bbaefcf99484f59a83b618d4ac455352f512fd2d68d7ee647d53f350d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v8_2a<a id="a9ffca842bbaefcf99484f59a83b618d4a8ae0544e8c0ae188e328279be14e4e53"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v8_1a<a id="a9ffca842bbaefcf99484f59a83b618d4a4e8c5a248d17f31e627d9105ddeef945"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v8<a id="a9ffca842bbaefcf99484f59a83b618d4a476c85c6da91c99d7aaade451bd18361"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v8r<a id="a9ffca842bbaefcf99484f59a83b618d4a1185d2fec5230b7b356db168f5b33b8d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v8m_baseline<a id="a9ffca842bbaefcf99484f59a83b618d4a782e22ec2166acb2925666b1fdcf87be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v8m_mainline<a id="a9ffca842bbaefcf99484f59a83b618d4a0f762073e648e99a9513ac450cae6504"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v8_1m_mainline<a id="a9ffca842bbaefcf99484f59a83b618d4ac0e610ea380b0a0ebb52353ed1a0b1cd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v7<a id="a9ffca842bbaefcf99484f59a83b618d4a0ebf9bc3153a34e39fb7f2b5adc4a549"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v7em<a id="a9ffca842bbaefcf99484f59a83b618d4ab8efff655ba87c9dfdd350b51a3d4345"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v7m<a id="a9ffca842bbaefcf99484f59a83b618d4a56d9342dc07ff0e1a21a3906fe31957c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v7s<a id="a9ffca842bbaefcf99484f59a83b618d4a8c30db3aef5173efcffcfbb21a083a64"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v7k<a id="a9ffca842bbaefcf99484f59a83b618d4a310c3af47d446eeaea76dd7ce69241f5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v7ve<a id="a9ffca842bbaefcf99484f59a83b618d4a7688e046378ef49d94118935e9bdc139"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v6<a id="a9ffca842bbaefcf99484f59a83b618d4a6f712f6f866568eb3e0b2f7aa652fa35"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v6m<a id="a9ffca842bbaefcf99484f59a83b618d4adcfb053d1ad63024466047a1c6a92ff3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v6k<a id="a9ffca842bbaefcf99484f59a83b618d4a5e3ffc6475a86a4e2040e08b27dab792"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v6t2<a id="a9ffca842bbaefcf99484f59a83b618d4a01fcbdd4fbb3ddfc02aeeea9de057404"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v5<a id="a9ffca842bbaefcf99484f59a83b618d4a65a1a4e325bfede2c90fe1a5c6133bb2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v5te<a id="a9ffca842bbaefcf99484f59a83b618d4ac7b6c0c4bacdf3e9f70a4d97348fce9e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMSubArch_v4t<a id="a9ffca842bbaefcf99484f59a83b618d4accd10f70cf09c8a1612e20f13675f06c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AArch64SubArch_arm64e<a id="a9ffca842bbaefcf99484f59a83b618d4a68fc64acd599f1efceab58c5b1c948c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AArch64SubArch_arm64ec<a id="a9ffca842bbaefcf99484f59a83b618d4ac4c8930e0836b52270b435d71f98bdb0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KalimbaSubArch_v3<a id="a9ffca842bbaefcf99484f59a83b618d4a977ada971b681fd292c46b933b179a2d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KalimbaSubArch_v4<a id="a9ffca842bbaefcf99484f59a83b618d4abf52302217787a19c1c051caf6e9846a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KalimbaSubArch_v5<a id="a9ffca842bbaefcf99484f59a83b618d4acb11740734f6a18e96b94096142157e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MipsSubArch_r6<a id="a9ffca842bbaefcf99484f59a83b618d4a06ae0d5f23c7c3ab80c4a241a7489385"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PPCSubArch_spe<a id="a9ffca842bbaefcf99484f59a83b618d4af9352d351703c7abc15682e3cacbd872"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPIRVSubArch_v10<a id="a9ffca842bbaefcf99484f59a83b618d4a28f0d364a91de157afe87b7a37f4482f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPIRVSubArch_v11<a id="a9ffca842bbaefcf99484f59a83b618d4af683dac34822e36580d0a321f68af416"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPIRVSubArch_v12<a id="a9ffca842bbaefcf99484f59a83b618d4abbfc31485ff4538616ec4781b43e84ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPIRVSubArch_v13<a id="a9ffca842bbaefcf99484f59a83b618d4a2aa494dc61832706e97f2e3754d08fed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPIRVSubArch_v14<a id="a9ffca842bbaefcf99484f59a83b618d4abe4d0a4aeeee8ba9fad55d5be3375c0a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPIRVSubArch_v15<a id="a9ffca842bbaefcf99484f59a83b618d4a56d1bb97744ae0c6b4a62d7057b8b3c9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPIRVSubArch_v16<a id="a9ffca842bbaefcf99484f59a83b618d4a4c3a9a3e3252bd79135d70a26bffb83b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DXILSubArch_v1_0<a id="a9ffca842bbaefcf99484f59a83b618d4a954e732fd72626ce869a6b38c050495d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DXILSubArch_v1_1<a id="a9ffca842bbaefcf99484f59a83b618d4a202ec88c46325bdf865ca5a1f5819cb0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DXILSubArch_v1_2<a id="a9ffca842bbaefcf99484f59a83b618d4a0e4443406aadf87efa04d1ebeb8bec3a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DXILSubArch_v1_3<a id="a9ffca842bbaefcf99484f59a83b618d4a52965fe3bf486e8497500b37cab6273a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DXILSubArch_v1_4<a id="a9ffca842bbaefcf99484f59a83b618d4af083ca354398e0eba40123becd94226f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DXILSubArch_v1_5<a id="a9ffca842bbaefcf99484f59a83b618d4a9b088b1eec5001ea047b8bcf2d1e0921"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DXILSubArch_v1_6<a id="a9ffca842bbaefcf99484f59a83b618d4ad09a2cbaf1d4a9851a4b332da0616e85"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DXILSubArch_v1_7<a id="a9ffca842bbaefcf99484f59a83b618d4a959c52d31d7bbee0a429ea61faf01bed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DXILSubArch_v1_8<a id="a9ffca842bbaefcf99484f59a83b618d4ad54b83d8c0ad287435344c7693fbe686"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LatestDXILSubArch<a id="a9ffca842bbaefcf99484f59a83b618d4a243270a1b69b4a6ac763fe4317e0528d"></a></td>
<td class="doxyEnumItemDescription"> (= DXILSubArch_v1_8)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>

</div>
</div>

### VendorType {#a96fe35195867c94aef1adf2ad0e20eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Triple::VendorType </td>
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
<td class="doxyEnumItemName">UnknownVendor<a id="a96fe35195867c94aef1adf2ad0e20eeca0f632276cf5b78ab97257d7f90b7f97f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Apple<a id="a96fe35195867c94aef1adf2ad0e20eeca674d908c8b0ebe1880f8c8d651eda9e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PC<a id="a96fe35195867c94aef1adf2ad0e20eecafbca4de1e7e0ce699db11feb6a205b32"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCEI<a id="a96fe35195867c94aef1adf2ad0e20eecaf8cf55a2ccb688a02134bd768c9a1a3d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Freescale<a id="a96fe35195867c94aef1adf2ad0e20eeca919656f12c161f60c585b6ea65c77f9a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IBM<a id="a96fe35195867c94aef1adf2ad0e20eecae7589347388e13a416edcb71a946416c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImaginationTechnologies<a id="a96fe35195867c94aef1adf2ad0e20eeca9e259de1548e02615004c538112d3aab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MipsTechnologies<a id="a96fe35195867c94aef1adf2ad0e20eecadc6b40589adfbd4756bf72561c69a8c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NVIDIA<a id="a96fe35195867c94aef1adf2ad0e20eecaeb014b23b113a1cda5058e4e31aca881"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CSR<a id="a96fe35195867c94aef1adf2ad0e20eecaf2892bfd7e664cbdc7ced8ae9c15ca33"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMD<a id="a96fe35195867c94aef1adf2ad0e20eeca77be73c19a4451fa0580ac5b9018357b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mesa<a id="a96fe35195867c94aef1adf2ad0e20eecaa29f6dfe49ede82d55ad9310efd3582c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUSE<a id="a96fe35195867c94aef1adf2ad0e20eeca841dde16a0ee702c5b7aeda162c85e0c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpenEmbedded<a id="a96fe35195867c94aef1adf2ad0e20eeca5881a9306181e4330e92688656a52f4c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Intel<a id="a96fe35195867c94aef1adf2ad0e20eecac949231cdefe4cbb0f48febd5fda4ce7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastVendorType<a id="a96fe35195867c94aef1adf2ad0e20eecad01cec7eeab01443a5a06dadc9ed86ca"></a></td>
<td class="doxyEnumItemDescription"> (= Intel)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Arch {#a98033956d2c805e5654718668623d53d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArchType llvm::Triple::Arch {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The parsed arch type.</p>

<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>

</div>
</div>

### Data {#a1743babb7e87104be8a0e357342e4a00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::Triple::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>

</div>
</div>

### Environment {#a5cbedbcd276055a53b0038221b131b7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EnvironmentType llvm::Triple::Environment {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The parsed Environment type.</p>

<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>

</div>
</div>

### ObjectFormat {#abc57e811c09e0487d3a29bac39b62faf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectFormatType llvm::Triple::ObjectFormat {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The object format type.</p>

<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>

</div>
</div>

### OS {#acfc30435951b5d0e9909f1a8bae62b4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OSType llvm::Triple::OS {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The parsed OS type.</p>

<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>

</div>
</div>

### SubArch {#ad601895281985ce2950af09921eaca87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubArchType llvm::Triple::SubArch {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The parsed subarchitecture type.</p>

<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>

</div>
</div>

### Vendor {#abec3316862206317ea114d6eeffddc61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VendorType llvm::Triple::Vendor {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The parsed vendor type.</p>

<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getCanonicalVersionForOS() {#acb80731bb9cdd5bbf4deaa30512dd327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple Triple::getCanonicalVersionForOS (<a href="#a3cfefc755ab656000934f91193afb1cd">OSType</a> OSKind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> &amp; Version)</td>
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

<p>Returns a canonicalized OS version number for the specified OS.</p>

<p>Declaration at line 1268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 2154 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075">MacOSX</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Normalization

### CanonicalForm {#a1d5b377df30da16764880240c5c6b02e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::Triple::CanonicalForm </td>
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

<p>Canonical form.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ANY<a id="a1d5b377df30da16764880240c5c6b02ea8e1bde3c3d303163521522cf1d62f21f"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">THREE_IDENT<a id="a1d5b377df30da16764880240c5c6b02ea067527255c8461205d0762c7773b4ca1"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FOUR_IDENT<a id="a1d5b377df30da16764880240c5c6b02ea15f882feb4278a3e0ecdca2dc5bac572"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIVE_IDENT<a id="a1d5b377df30da16764880240c5c6b02ea072f18759c7194d6ca2de60d81ea9168"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>

</div>
</div>

### normalize {#a33c480b0848b82efb6835907a88e7b22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::Triple::normalize (<a href="#a1d5b377df30da16764880240c5c6b02e">CanonicalForm</a> Form=<a href="#a1d5b377df30da16764880240c5c6b02ea8e1bde3c3d303163521522cf1d62f21f">CanonicalForm::ANY</a>)</td>
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

<p>Return the normalized form of this triple's string.</p>

<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a1d5b377df30da16764880240c5c6b02ea8e1bde3c3d303163521522cf1d62f21f">ANY</a> and <a href="#a5c2fb6bace55f9b58ed0ba9fe363299e">normalize</a>.</p>

</div>
</div>

### normalize {#a5c2fb6bace55f9b58ed0ba9fe363299e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string Triple::normalize (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="#a1d5b377df30da16764880240c5c6b02e">CanonicalForm</a> Form=<a href="#a1d5b377df30da16764880240c5c6b02ea8e1bde3c3d303163521522cf1d62f21f">CanonicalForm::ANY</a>)</td>
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

<p>Turn an arbitrary machine specification into the canonical triple form (or something sensible that the <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> class understands if nothing better can reasonably be done).</p>


<p>In particular, it handles the common case in which otherwise valid components are in the wrong order. <span class="doxyComputerOutput">Form</span> is used to specify the output canonical form.</p>


<p>Declaration at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1131 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a1778f5c464f88710033f7e11e84a9324a0ceb06180ab5fc86e9ad27563b538439">Android</a>, <a href="#a1d5b377df30da16764880240c5c6b02ea8e1bde3c3d303163521522cf1d62f21f">ANY</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a83e907e55fa50e093caa96a0aff96201aa943abc041caa1cc4c074bbf38b76267">COFF</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="#a1d5b377df30da16764880240c5c6b02ea072f18759c7194d6ca2de60d81ea9168">FIVE_IDENT</a>, <a href="#a1d5b377df30da16764880240c5c6b02ea15f882feb4278a3e0ecdca2dc5bac572">FOUR_IDENT</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a9ae632cfb346b34a2a80a7f70e1ee048">getDXILArchNameFromShaderModel</a>, <a href="#ada671e44e91b68a18f8a61f12dd1f475">getObjectFormatTypeName</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a73b4a675dd734e1efcab33de0d217a37">GNUEABI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ad3a9a5aa955e9b62ec11e4d3566d4594">parseArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a1d2990073fc241c3de22309696bf3314">parseEnvironment</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#acd920d1fcd9dc528687e8ab0df027fdd">parseFormat</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a96f0a5c666b924f50da56dede8092ae7">parseOS</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#af928c309977e80665cdc60d0b9c46d89">parseVendor</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="#a3cfefc755ab656000934f91193afb1cdac4081e09efdc53c28fc78e5ca68ea70a">ShaderModel</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/stringviewextras-h/#a5336c02c81ff675028496f2f2409d30a">starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eeca841dde16a0ee702c5b7aeda162c85e0c">SUSE</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="#a1d5b377df30da16764880240c5c6b02ea067527255c8461205d0762c7773b4ca1">THREE_IDENT</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">UnknownArch</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a6c32bcd90dff79307baf3147697ae1d3">UnknownEnvironment</a>, <a href="#a83e907e55fa50e093caa96a0aff96201af2f88d8b470958614a01866d4714b5a4">UnknownObjectFormat</a>, <a href="#a3cfefc755ab656000934f91193afb1cda4b110a50637320a1a0db33999b809ddd">UnknownOS</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eeca0f632276cf5b78ab97257d7f90b7f97f">UnknownVendor</a> and <a href="#a3cfefc755ab656000934f91193afb1cdafd0c0a465dca43ad44f79806a226a1ae">Win32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sys/#aab375071f641a086c0d7067635ccd3dc">llvm::sys::getProcessTriple</a>, <a href="/web-llvm/docs/api/groups/llvmctarget/#ga7ea7895c81baccbdbccc5a6bb8be4fb3">LLVMNormalizeTargetTriple</a>, <a href="#a33c480b0848b82efb6835907a88e7b22">normalize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab3e1cccbbbb64f0a0ae8546c703e9b81">llvm::SPIRVTranslateModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Constructors

### operator!= {#ae30aee607a7f1b0907b66becc29d5bd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; Other)</td>
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



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a15410866a30d89459a6f99034202e475">Triple</a>.</p>

</div>
</div>

### operator== {#ac2babdb16d78b57252b464a5c73d78f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; Other)</td>
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



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a15410866a30d89459a6f99034202e475">Triple</a>.</p>

</div>
</div>

### Triple {#a15410866a30d89459a6f99034202e475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Triple::Triple ()</td>
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

<p>Default constructor is the same as an empty string and leaves all triple fields unknown.</p>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>Referenced by <a href="#a13e7af62cc56f460209e36190829d78c">get32BitArchVariant</a>, <a href="#a424c4dc4d08741fa4615cc0c4ec956bd">get64BitArchVariant</a>, <a href="#adb7bb8c037a9662d31b148af4efa2a5a">getBigEndianArchVariant</a>, <a href="#a269e50214be37e2963f53f94518a1894">getLittleEndianArchVariant</a>, <a href="#ae86f9f850769a4896b883b0da1322a51">isCompatibleWith</a>, <a href="#a5fa1f16bd79509b687e8c593a048a225">isOSVersionLT</a>, <a href="#a8605d2bf7adf880652f2a4fe11ca050d">merge</a>, <a href="#ae30aee607a7f1b0907b66becc29d5bd3">operator!=</a>, <a href="#ac2babdb16d78b57252b464a5c73d78f1">operator==</a>, <a href="#a096c1f8d7977e175075e210101627e0b">setArchName</a>, <a href="#a58ffeec08324cdbd301158e5ef874cc3">setTriple</a> and <a href="#a3a8e516b5874b78eb8bc72e644d62ae5">Triple</a>.</p>

</div>
</div>

### Triple {#a5795a74557bb339afa955660ecb76247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::Triple (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Str)</td>
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

<p>Construct a triple from the string representation provided.</p>


<p>This stores the string representation and parses the various pieces into enum members.</p>


<p>Declaration at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1015 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a593094f6c13df699bd2cde1a1f40fec4">getDefaultFormat</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ae6c91532448c0be7978cf1bfcdaa11bb">GNU</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a21e1198b41cc86aafe10fcd5a6ca330b">GNUABI64</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a75fa362b8315ce952fde83ff09a4c599">GNUABIN32</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a023f1e73b058ea58dba15516382eed52">NoSubArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ad3a9a5aa955e9b62ec11e4d3566d4594">parseArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a1d2990073fc241c3de22309696bf3314">parseEnvironment</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#acd920d1fcd9dc528687e8ab0df027fdd">parseFormat</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a96f0a5c666b924f50da56dede8092ae7">parseOS</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ac784253baaaa3c7ac2760f3d9b71f1c1">parseSubArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#af928c309977e80665cdc60d0b9c46d89">parseVendor</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a88e653a89d15149cc7a68f88be360303">llvm::StringSwitch&lt; T, R &gt;::StartsWith</a>, <a href="#a6ad662bdf0613457ae9b81b47f5555b7">str</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">UnknownArch</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a6c32bcd90dff79307baf3147697ae1d3">UnknownEnvironment</a>, <a href="#a83e907e55fa50e093caa96a0aff96201af2f88d8b470958614a01866d4714b5a4">UnknownObjectFormat</a>, <a href="#a3cfefc755ab656000934f91193afb1cda4b110a50637320a1a0db33999b809ddd">UnknownOS</a> and <a href="#a96fe35195867c94aef1adf2ad0e20eeca0f632276cf5b78ab97257d7f90b7f97f">UnknownVendor</a>.</p>

</div>
</div>

### Triple {#a3a8e516b5874b78eb8bc72e644d62ae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::Triple (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; ArchStr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; VendorStr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; OSStr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a triple from string representations of the architecture, vendor, and OS.</p>


<p>This joins each argument into a canonical string representation and parses them into enum members. It leaves the environment unknown and omits it from the string representation.</p>


<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1055 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a593094f6c13df699bd2cde1a1f40fec4">getDefaultFormat</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ad3a9a5aa955e9b62ec11e4d3566d4594">parseArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a96f0a5c666b924f50da56dede8092ae7">parseOS</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ac784253baaaa3c7ac2760f3d9b71f1c1">parseSubArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#af928c309977e80665cdc60d0b9c46d89">parseVendor</a>, <a href="#a6ad662bdf0613457ae9b81b47f5555b7">str</a>, <a href="#a15410866a30d89459a6f99034202e475">Triple</a> and <a href="#a83e907e55fa50e093caa96a0aff96201af2f88d8b470958614a01866d4714b5a4">UnknownObjectFormat</a>.</p>

</div>
</div>

### Triple {#a2f144736db0877eaef0c6904afee0187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::Triple (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; ArchStr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; VendorStr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; OSStr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; EnvironmentStr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a triple from string representations of the architecture, vendor, OS, and environment.</p>


<p>This joins each argument into a canonical string representation and parses them into enum members.</p>


<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1070 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a593094f6c13df699bd2cde1a1f40fec4">getDefaultFormat</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ad3a9a5aa955e9b62ec11e4d3566d4594">parseArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a1d2990073fc241c3de22309696bf3314">parseEnvironment</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#acd920d1fcd9dc528687e8ab0df027fdd">parseFormat</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a96f0a5c666b924f50da56dede8092ae7">parseOS</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ac784253baaaa3c7ac2760f3d9b71f1c1">parseSubArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#af928c309977e80665cdc60d0b9c46d89">parseVendor</a>, <a href="#a6ad662bdf0613457ae9b81b47f5555b7">str</a> and <a href="#a83e907e55fa50e093caa96a0aff96201af2f88d8b470958614a01866d4714b5a4">UnknownObjectFormat</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Typed Component Access

### getArch {#a5fc23559f17bbe5ff83ec0fed0a5fdcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArchType llvm::Triple::getArch ()</td>
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

<p>Get the parsed architecture type of this triple.</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a32cf61958e13a95aaf8686f4c55aa873">llvm::TargetLibraryInfoImpl::addVectorizableFunctionsFromVecLib</a>, <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp/#ad498b62e948a8434f2f7bf34cd6ce16b">adjustInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/armelfmcasminfo/#a0a8f465f858ce8ee2c58a12eec797a02">llvm::ARMELFMCAsmInfo::ARMELFMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armmcasminfodarwin/#a9431bd9edb8400058b9caccf2c38f21e">llvm::ARMMCAsmInfoDarwin::ARMMCAsmInfoDarwin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#a435833d0fa51b89ed044e840a28833a0">llvm::CodeViewDebug::beginModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ae215c9475e5b6a8ae5efa8ff60202dfe">createAArch64MCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#ac87ba800a84c083b0ff262ecb6b7f2a4">createPPCMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#abb08ae2f213bc5b87540413de9b095a2">CreateVarArgHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#aeafb06413605da840d52ad76655540e8">createX86MCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a01e0861a16978fc748dd79c56e17e4f3">emplace</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#a95c1eb0bb9394b39e6edb45ae6a57bfe">llvm::CodeViewDebug::endFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis/#ae48345ba0c30a521aab65eeb28949d8f">llvm::X86_MC::X86MCInstrAnalysis::findPltEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#adbf8027ff0f01d2acccb979b5f79e5ca">llvm::AMDGPUSubtarget::get</a>, <a href="#a13e7af62cc56f460209e36190829d78c">get32BitArchVariant</a>, <a href="#a424c4dc4d08741fa4615cc0c4ec956bd">get64BitArchVariant</a>, <a href="#a261b9412ba2231505fc5d6ffa7d3a01a">getArchPointerBitWidth</a>, <a href="#adb7bb8c037a9662d31b148af4efa2a5a">getBigEndianArchVariant</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#a5a24823d504d2c91c152e69250b2197d">llvm::SubtargetFeatures::getDefaultSubtargetFeatures</a>, <a href="#a6ac5d7614594ccea16725535d111652a">getDXILVersion</a>, <a href="#adcf64addbfd5833e0c59117fee9bedec">getiOSVersion</a>, <a href="#a269e50214be37e2963f53f94518a1894">getLittleEndianArchVariant</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcasminfo/#a081e0d017dbcb21393b0e55d70d4550c">llvm::AMDGPUMCAsmInfo::getMaxInstLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a2d0c61cd3e4d53626ffdb34031766f08">llvm::AMDGPU::IsaInfo::getMaxWorkGroupsPerCU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a12457438c2b018b673e22e0253e466c4">llvm::AMDGPU::getMCReg</a>, <a href="#a9b7155e7913c06217d85f6a7a3250315">getMinimumSupportedOSVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#ad9b5eba01208d43c3c753251be70778a">llvm::memtag::getPC</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#ab5019ff9e3502f422f3d8668201f5756">llvm::object::ELFObjectFileBase::getPltEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf156ed576f5bcdb93911b50b775c8ac">llvm::getSubDirectoryPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a7d269a83a714b7924ac1d67e52655c73">llvm::lto::getThinLTODefaultCPU</a>, <a href="#a619b009238bd7e0a7bb68afe88f2d2fd">getTrampolineSize</a>, <a href="#a6e60a7cae0edfa1045ed0e35c9b55088">getVulkanVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2793bce814c8f8c6fc2f41d4156a4ebb">llvm::TargetLoweringObjectFileELF::Initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#a623777b0f29b96919b50ce21c13aa6ae">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::insertThunks</a>, <a href="#ad953e410aea43848740978d9a6529a82">isAArch64</a>, <a href="#a2ec13d6660c3676bc8f76c8b7f14f3e8">isAArch64</a>, <a href="#a92da6cf2a6b4ce43d5c5e4ef110511aa">isAMDGCN</a>, <a href="#a9318bd992483581cc335e1a33782ea45">isAMDGPU</a>, <a href="#adb3675c020f17151a02604b14c8cdb77">isArch16Bit</a>, <a href="#ae11d6e273225164d9da0c6cad55e093d">isArch32Bit</a>, <a href="#a9e0d7431e635bbbf753602d214d89f0e">isArch64Bit</a>, <a href="#a846115743c5cbbf80216168ad22f906c">isARM</a>, <a href="#a32dff8f6f7ea462f82443a33fdf1e4ac">isArm64e</a>, <a href="#a291cf24ece30f33f071b7f62ee0b9ec1">isBPF</a>, <a href="#ae86f9f850769a4896b883b0da1322a51">isCompatibleWith</a>, <a href="#a64f24694a89d710b9a7f59e1f2df0d12">isCSKY</a>, <a href="#af8167b32a55564d0d023cdc3bcd5b0b6">isDXIL</a>, <a href="#a45678567c4d2b54e70800daa41897207">isLittleEndian</a>, <a href="#a93994a01f6ca3fdd3daf286e2712a465">isLoongArch32</a>, <a href="#a66a1a1858e17b6bcfcbbb1d5229d275e">isLoongArch64</a>, <a href="#a73717ef7418a714f20be268c55a2c19e">isMIPS32</a>, <a href="#a52f9355613c6f3388d5761349926d835">isMIPS64</a>, <a href="#a9871d348bbc1e85bd1daacb428238707">isNVPTX</a>, <a href="#a0338eabc8ab4dff6368bdfae6ec94cbc">isPPC</a>, <a href="#a5fbc3fe5e4f1e0f9515cfac36293b1c8">isPPC32</a>, <a href="#ae08707e2e2afe994828112fbe8a89817">isPPC32SecurePlt</a>, <a href="#ab61d338cbe7892ab484e97c9b0c8c8c9">isPPC64</a>, <a href="#a1ab21929777b807678f98c873cdd7c7c">isPPC64ELFv2ABI</a>, <a href="#a17cc069acf48bda2ac7451a56536cb0c">isPS4</a>, <a href="#ad76134ab5457867366f4ed43758bb8d6">isPS5</a>, <a href="#a578c0e35b3e3ed8c73e610a0882a9d6a">isRISCV32</a>, <a href="#a64b2600935100a4be30d8a364609e427">isRISCV64</a>, <a href="#a692addc79837dc704398400593123895">isSPARC32</a>, <a href="#aa0e575c51232ced86460d9ae83f96cbc">isSPARC64</a>, <a href="#a1c0737f9edc41d1a0ec4b5ec9a7e8b87">isSPIR</a>, <a href="#ad77183da26fd51a168f2cedcd0df3561">isSPIRV</a>, <a href="#aba6fc3ce3bf1813201d150730c918d70">isSPIRVLogical</a>, <a href="#ade08dbf7a3d70b46b55c4257b3a536de">isSystemZ</a>, <a href="#a17b2679f91f697a4ffe46b872152e25b">isThumb</a>, <a href="#afeb095611dceaee172b9ab66a9f765ba">isVE</a>, <a href="#acf7f07dbe7dd1f7edd291b75005280bb">isWasm</a>, <a href="#ac0544a852d0033d3980285dbd1133ac6">isWindowsArm64EC</a>, <a href="#a31d94b95418472bb1179f7c130ad3667">isX86</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a983c712b48551572f722178a15e95d27">llvm::jitlink::LinkGraph::LinkGraph</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a85a69009ec328d5835241f56fb62cc6d">llvm::TargetRegistry::lookupTarget</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a41245c88cdf19ddbfe8a2dffba0a500d">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::LowerTypeTestsModule</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxmcasminfo/#a198606773a0fd35284257608ba615fa5">llvm::NVPTXMCAsmInfo::NVPTXMCAsmInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/omp/ompcontext/#a4d6214c1b52e5b83b8c96f868cfb14f2">llvm::omp::OMPContext::OMPContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#aac98d18ebaf02ce89cd8783f59aad2d0">llvm::ifs::parseTriple</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a18ff6139760982f4640e0ea26da81ba4">llvm::orc::LLJITBuilderState::prepareForConstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopidiomrecognition-cpp-/hexagonloopidiomrecognize/#a6ffbdd584e20d3107954e86273e714e4">anonymous{HexagonLoopIdiomRecognition.cpp}::HexagonLoopIdiomRecognize::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp/#a8fe56fea0dcbc78bba2366b7e2918a41">runImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-xrayinstrumentation-cpp-/xrayinstrumentation/#a4fb91ea8621a93ca73b483592ac6b061">anonymous{XRayInstrumentation.cpp}::XRayInstrumentation::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284276bdba816c71f6c16ee08e842b41">llvm::FastISel::selectXRayCustomEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a8c80b7d55789b6712c22642d4f94b90d">llvm::FastISel::selectXRayTypedEvent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf2ff3020b311fe77e208f80459017aa">llvm::setGlobalVariableLargeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a49ae9dcb1b15c8bd79c384ddf3956db8">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::shouldBuildRelLookupTables</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hwaddresssanitizer-cpp-/#a99dd73d8d6f6807d5507f969962486f4">anonymous{HWAddressSanitizer.cpp}::shouldInstrumentWithCalls</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hwaddresssanitizer-cpp-/#a6b0715e3604a90c77e379a370f1b133a">anonymous{HWAddressSanitizer.cpp}::shouldUsePageAliases</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcelfmcasminfo/#a888a362f41dfb42c444b7f5fec9f2bcc">llvm::SparcELFMCAsmInfo::SparcELFMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86mcasminfognucoff/#a962aeeaf657c538ec248271056d017ec">llvm::X86MCAsmInfoGNUCOFF::X86MCAsmInfoGNUCOFF</a> and <a href="/web-llvm/docs/api/classes/llvm/x86mcasminfomicrosoft/#ac3d14e522888ac8ead6f614968a86899">llvm::X86MCAsmInfoMicrosoft::X86MCAsmInfoMicrosoft</a>.</p>

</div>
</div>

### getDriverKitVersion {#a72667fa2e9534947a4794acf8958f884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple Triple::getDriverKitVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the version number as with getOSVersion.</p>

<p>Declaration at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1527 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a3cfefc755ab656000934f91193afb1cda600aa0b72f321a0cdf0e4b3f38b9b6c8">DriverKit</a>, <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>, <a href="#a024faa768c9d7b624a68980113f92693">getOSVersion</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>

</div>
</div>

### getDXILVersion {#a6ac5d7614594ccea16725535d111652a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple Triple::getDXILVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the DXIL version number from the OSVersion and DXIL version (SubArch).</p>


<p>This should only be called with DXIL triples.</p>


<p>Declaration at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1564 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154a9ca957896440ddfeeedda9c05723c150">dxil</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#ad2d9e5a5c22d594a05d4feae337de252">getArchName</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a9ae632cfb346b34a2a80a7f70e1ee048">getDXILArchNameFromShaderModel</a>, <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>, <a href="#a483bbccede7948c656b0bd339f39218f">getOSName</a>, <a href="#a2f6aa922f9f6991e7d8aecb147e08fd4">getSubArch</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a023f1e73b058ea58dba15516382eed52">NoSubArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a2a17730f2d2df672ebcf51b00eb2ab55">parseVersionFromName</a> and <a href="#a3cfefc755ab656000934f91193afb1cdac4081e09efdc53c28fc78e5ca68ea70a">ShaderModel</a>.</p>

</div>
</div>

### getEnvironment {#a6beb910ab0112de8679b6d2703351384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EnvironmentType llvm::Triple::getEnvironment ()</td>
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

<p>Get the parsed environment type of this triple.</p>

<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad838b75c8aa824335f1f1642d5d78545">llvm::createAArch64beAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a676b531bfbeddd2a9614c12d21ad4c88">llvm::createAArch64leAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a01e0861a16978fc748dd79c56e17e4f3">emplace</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#a339bb20fead6005cd1cc37f479650617">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#aa92ad486f7d87701440dd069319134d5">llvm::ARM::getARMCPUForArch</a>, <a href="#ade97ab011dc19854c9886f2c6d8ecc66">getEnvironmentVersionString</a>, <a href="#a2ec13d6660c3676bc8f76c8b7f14f3e8">isAArch64</a>, <a href="#a47bfd723026a27a754135ac44f10b9b8">isABIN32</a>, <a href="#a3f3873f607a36e40241082727fef44db">isAndroid</a>, <a href="#ae86f9f850769a4896b883b0da1322a51">isCompatibleWith</a>, <a href="#af9611bb364d25198d356aa20527fcffb">isGNUEnvironment</a>, <a href="#a287017c7824dea2df018a3e237cf2b52">isHardFloatABI</a>, <a href="#af6d6a4d950ccaa3be4ca4ff2f2169090">isKnownWindowsMSVCEnvironment</a>, <a href="#ad7328346f2f8d6b9d897608882bc7758">isMacCatalystEnvironment</a>, <a href="#a7bbfb6d92b2d86cf613bc425e5446b00">isMusl</a>, <a href="#ad59e9ffe0d450e94f287c540ad043130">isOpenHOS</a>, <a href="#afd88a4e5f804888b864374a454f6d13f">isShaderStageEnvironment</a>, <a href="#a6a66d02819186762f85145d632f9f81f">isSimulatorEnvironment</a>, <a href="#a38835c05d2e959d03033c304cd94a1b1">isTargetEHABICompatible</a>, <a href="#ae09fbe778f8a1f090e6d3fb5175bdb4b">isTime64ABI</a>, <a href="#a4aff54e7e4562b21d5762a6ca406f9f7">isWindowsCoreCLREnvironment</a>, <a href="#aa0fd88c696cfbb5c2648fe705dcdef5c">isWindowsCygwinEnvironment</a>, <a href="#a398f3f1f57fae295ca4ae75a3b56fa59">isWindowsGNUEnvironment</a>, <a href="#afdd0d3d27ef11fd6ad21da63c3979d77">isWindowsItaniumEnvironment</a>, <a href="#aed5b9fcccfe88a419343c80064d44d74">isWindowsMSVCEnvironment</a> and <a href="#a292887fa6b4aa078f520d5884dda7ad9">isX32</a>.</p>

</div>
</div>

### getEnvironmentVersion {#a5ad45f83c98f9639777cb9924cef58fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple Triple::getEnvironmentVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the version number from the OS name component of the triple, if present.</p>


<p>For example, "fooos1.2.3" would return (1, 2, 3).</p>


<p>Declaration at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1386 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#ade97ab011dc19854c9886f2c6d8ecc66">getEnvironmentVersionString</a> and <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a2a17730f2d2df672ebcf51b00eb2ab55">parseVersionFromName</a>.</p>


<p>Referenced by <a href="#a13b920f74d7ae331cfd2740a790de541">isAndroidVersionLT</a>.</p>

</div>
</div>

### getiOSVersion {#adcf64addbfd5833e0c59117fee9bedec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple Triple::getiOSVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the version number as with getOSVersion.</p>


<p>This should only be called with IOS or generic triples.</p>


<p>Declaration at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1472 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">aarch64</a>, <a href="#a3cfefc755ab656000934f91193afb1cda0824a8c56de913d60c6f55edc0ac3148">Darwin</a>, <a href="#a3cfefc755ab656000934f91193afb1cda600aa0b72f321a0cdf0e4b3f38b9b6c8">DriverKit</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>, <a href="#a024faa768c9d7b624a68980113f92693">getOSVersion</a>, <a href="#a3cfefc755ab656000934f91193afb1cdafad6e6763679be1478d9283a7344d243">IOS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075">MacOSX</a>, <a href="#a3cfefc755ab656000934f91193afb1cda2838cf6df0f09591c50d752d46c4350d">TvOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>, <a href="#a3cfefc755ab656000934f91193afb1cda87a3c8454473c64f6d605ebd757759ad">WatchOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cdabb5225659a201976ce2594df579e3623">XROS</a>.</p>

</div>
</div>

### getMacOSXVersion {#aa0a7f9a135ee2e5c73cb076f6867ce8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Triple::getMacOSXVersion (<a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> &amp; Version)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the version number as with getOSVersion and then translate generic "darwin" versions to the corresponding OS X versions.</p>


<p>This may also be called with IOS triples but the OS X version number is just set to a constant 10.4.0 in that case. Returns true if successful.</p>


<p>Declaration at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1427 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a3cfefc755ab656000934f91193afb1cda0824a8c56de913d60c6f55edc0ac3148">Darwin</a>, <a href="#a3cfefc755ab656000934f91193afb1cda600aa0b72f321a0cdf0e4b3f38b9b6c8">DriverKit</a>, <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>, <a href="#a024faa768c9d7b624a68980113f92693">getOSVersion</a>, <a href="#a3cfefc755ab656000934f91193afb1cdafad6e6763679be1478d9283a7344d243">IOS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075">MacOSX</a>, <a href="#a3cfefc755ab656000934f91193afb1cda2838cf6df0f09591c50d752d46c4350d">TvOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>, <a href="#a3cfefc755ab656000934f91193afb1cda87a3c8454473c64f6d605ebd757759ad">WatchOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cdabb5225659a201976ce2594df579e3623">XROS</a>.</p>

</div>
</div>

### getObjectFormat {#a2e265a0d332c3e2db0acf0c7afd4175d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectFormatType llvm::Triple::getObjectFormat ()</td>
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

<p>Get the object format for this triple.</p>

<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp/#a8f6ab6658167369fdde830fd3c8d287c">createARMAsmBackend</a>, <a href="#ade97ab011dc19854c9886f2c6d8ecc66">getEnvironmentVersionString</a>, <a href="#ae86f9f850769a4896b883b0da1322a51">isCompatibleWith</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofiler-cpp-/memprofiler/#a7421c242cf99bb3c1709262edadc96ff">anonymous{MemProfiler.cpp}::MemProfiler::isInterestingMemoryAccess</a>, <a href="#a6300d761fd69580d711fad99b934950a">isOSBinFormatCOFF</a>, <a href="#a7df3ae0918bd700a9c8507e3b158e06f">isOSBinFormatDXContainer</a>, <a href="#aea6d215256ae43bc9149bf41f2cc7694">isOSBinFormatELF</a>, <a href="#a388a623b8ab44f9d44d0525b548fcff8">isOSBinFormatGOFF</a>, <a href="#a444e46ff0a17a6c9480eb151bd42c9bc">isOSBinFormatMachO</a>, <a href="#a1e1c6e3713e5c441d358239f9fac89a7">isOSBinFormatWasm</a>, <a href="#a804d3966ad6c4daafeb8a7ae31b8ae2d">isOSBinFormatXCOFF</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a41245c88cdf19ddbfe8a2dffba0a500d">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::LowerTypeTestsModule</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a8c75c94fa169456ebdef2337504928e6">llvm::MCContext::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/gdbjitdebuginforegistrationplugin/#a01913c5e7fe810e72e2526d49ca29636">llvm::orc::GDBJITDebugInfoRegistrationPlugin::modifyPassConfig</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf2ff3020b311fe77e208f80459017aa">llvm::setGlobalVariableLargeSection</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/threadsanitizer-cpp/#a0bb37c4d9d72e23c0da8cafdb59f466a">shouldInstrumentReadWriteFromAddress</a>.</p>

</div>
</div>

### getOS {#a5a777de4cd152c5b22b9d28439326d50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OSType llvm::Triple::getOS ()</td>
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

<p>Get the parsed operating system type of this triple.</p>

<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armelfmcasminfo/#a0a8f465f858ce8ee2c58a12eec797a02">llvm::ARMELFMCAsmInfo::ARMELFMCAsmInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad838b75c8aa824335f1f1642d5d78545">llvm::createAArch64beAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a676b531bfbeddd2a9614c12d21ad4c88">llvm::createAArch64leAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp/#a8f6ab6658167369fdde830fd3c8d287c">createARMAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acdca173360fb2277a90f6e69685ce295">llvm::createAVRAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a691c09716f1274d5e4c4b8f35393f2da">llvm::createM68kAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9f09be1a3af90f08040057a4a330a73">llvm::createSparcAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e2f30307ffe41c5d4e80899ee135826">llvm::createSystemZMCAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b0f671e47ceee3b9db1be426a79e779">llvm::createVEAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae35ef2e57b2c31572d967cb78484ffaa">llvm::createX86_32AsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a306674e8951ad0f9c77cda2f70219ab9">llvm::createX86_64AsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af32e200fafb3ce3f4a7ed1546ab34219">llvm::createXtensaMCAsmBackend</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#aa4e7f162a6130db44eb584e71f19ae67">llvm::AMDGPUAsmPrinter::doFinalization</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a01e0861a16978fc748dd79c56e17e4f3">emplace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#aa92ad486f7d87701440dd069319134d5">llvm::ARM::getARMCPUForArch</a>, <a href="#a72667fa2e9534947a4794acf8958f884">getDriverKitVersion</a>, <a href="#a6ac5d7614594ccea16725535d111652a">getDXILVersion</a>, <a href="#adcf64addbfd5833e0c59117fee9bedec">getiOSVersion</a>, <a href="#aa0a7f9a135ee2e5c73cb076f6867ce8e">getMacOSXVersion</a>, <a href="#a9b7155e7913c06217d85f6a7a3250315">getMinimumSupportedOSVersion</a>, <a href="#a024faa768c9d7b624a68980113f92693">getOSVersion</a>, <a href="#a6e60a7cae0edfa1045ed0e35c9b55088">getVulkanVersion</a>, <a href="#a07060601788098311a70d6e43327cb08">getWatchOSVersion</a>, <a href="#ae86f9f850769a4896b883b0da1322a51">isCompatibleWith</a>, <a href="#a1f396e16b49f3277fc279f94a12d03a5">isDriverKit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3d357ec8432b58835aaa34defcc4eff9">llvm::AMDGPU::isHsaAbi</a>, <a href="#ac36bf25c234d956997781778c866808e">isiOS</a>, <a href="#aa6a7d5d218ef0d2334fe24eaf997bbb6">isMacOSX</a>, <a href="#a0092ef6558c242caa4916fbd7fd8da34">isMacOSXVersionLT</a>, <a href="#a98cf8213993e03f8b57f294bd66cb40c">isOSAIX</a>, <a href="#a03aa5e23acb1aace7f2d2014cd3382ab">isOSDragonFly</a>, <a href="#ac044f740fee04796ffe5ba17fdc3fa0c">isOSEmscripten</a>, <a href="#aa98a01c1d72fde0f87823d204dc98334">isOSFreeBSD</a>, <a href="#ae891092a64f3b737dcba557a8450587c">isOSFuchsia</a>, <a href="#ac517c6287b37ff0764afbb97f2a56b51">isOSGlibc</a>, <a href="#af70af5dfe0ad906d51c7ca09d13a3e2e">isOSHaiku</a>, <a href="#a26f50a368caaea38084bc9b40769ade1">isOSHurd</a>, <a href="#ad3d505c1a9bc7380a73561d84d063ca9">isOSIAMCU</a>, <a href="#a57ba86412d0c09795efe03bd06b8dba1">isOSKFreeBSD</a>, <a href="#a898af817f450422b11443c35c99e64da">isOSLinux</a>, <a href="#a96c0dd9835688584c4d9121e8be7704f">isOSLiteOS</a>, <a href="#a0dd94ab3854e0421e795ce04ee3babf9">isOSNaCl</a>, <a href="#a3d98f3cc4fe2adddfa98dc0dbee55bdb">isOSNetBSD</a>, <a href="#a6e54a3851d12ab87ef42ebff942bac13">isOSOpenBSD</a>, <a href="#a6b1293b8705b0bd5ae5c783029399016">isOSSerenity</a>, <a href="#a565d07b44e55cbff02db88c1d5cf3cb1">isOSSolaris</a>, <a href="#a70cdd4fe5787c4383db8bbd21570f062">isOSUnknown</a>, <a href="#a1bcb02d757ae9d46b7720d607ce67d76">isOSWASI</a>, <a href="#a7736bfc4c1afef875ecf02f2a7701fe3">isOSWindows</a>, <a href="#a6b121909a2e76bd11b0673b0eeb58b25">isOSzOS</a>, <a href="#ae08707e2e2afe994828112fbe8a89817">isPPC32SecurePlt</a>, <a href="#a1ab21929777b807678f98c873cdd7c7c">isPPC64ELFv2ABI</a>, <a href="#a17cc069acf48bda2ac7451a56536cb0c">isPS4</a>, <a href="#ad76134ab5457867366f4ed43758bb8d6">isPS5</a>, <a href="#a74c3ac300c06a2c491256534b99b08b9">isShaderModelOS</a>, <a href="#abf440ac7b84052680788f233de6bcdb6">isTvOS</a>, <a href="#a76b2f9ab09b41fed3ffeb43eda2533d8">isUEFI</a>, <a href="#ad1a8e844d6b87311c662964dd8826358">isVulkanOS</a>, <a href="#ac2eddca981f187178a53969d88465b4c">isWatchOS</a>, <a href="#aaba295444f638da56e58010cf7fb091d">isXROS</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a41245c88cdf19ddbfe8a2dffba0a500d">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::LowerTypeTestsModule</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ab870ac74feb45bb48a75027da41c0784">llvm::SITargetLowering::shouldUseLDSConstAddress</a>.</p>

</div>
</div>

### getOSMajorVersion {#ae6bb6cb4330e31951d06537d80c39e62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Triple::getOSMajorVersion ()</td>
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

<p>Return just the major version number, this is specialized because it is a common query.</p>

<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#a56a72b8793b8e0df7217c9b19a83320b">llvm::VersionTuple::getMajor</a> and <a href="#a024faa768c9d7b624a68980113f92693">getOSVersion</a>.</p>


<p>Referenced by <a href="#ae08707e2e2afe994828112fbe8a89817">isPPC32SecurePlt</a> and <a href="#a1ab21929777b807678f98c873cdd7c7c">isPPC64ELFv2ABI</a>.</p>

</div>
</div>

### getOSVersion {#a024faa768c9d7b624a68980113f92693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple Triple::getOSVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the version number from the OS name component of the triple, if present.</p>


<p>For example, "fooos1.2.3" would return (1, 2, 3).</p>


<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1413 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>, <a href="#a483bbccede7948c656b0bd339f39218f">getOSName</a>, <a href="#a8192d4072e4aaba803248250d1faf61c">getOSTypeName</a>, <a href="#a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075">MacOSX</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a2a17730f2d2df672ebcf51b00eb2ab55">parseVersionFromName</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="#a72667fa2e9534947a4794acf8958f884">getDriverKitVersion</a>, <a href="#adcf64addbfd5833e0c59117fee9bedec">getiOSVersion</a>, <a href="#aa0a7f9a135ee2e5c73cb076f6867ce8e">getMacOSXVersion</a>, <a href="#ae6bb6cb4330e31951d06537d80c39e62">getOSMajorVersion</a>, <a href="#a6e60a7cae0edfa1045ed0e35c9b55088">getVulkanVersion</a>, <a href="#a07060601788098311a70d6e43327cb08">getWatchOSVersion</a>, <a href="#a5fa1f16bd79509b687e8c593a048a225">isOSVersionLT</a>, <a href="#abc7c65abde53e1e420cab20d84d49cbb">isOSVersionLT</a>, <a href="#ae08707e2e2afe994828112fbe8a89817">isPPC32SecurePlt</a>, <a href="#a1ab21929777b807678f98c873cdd7c7c">isPPC64ELFv2ABI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a44bd2d03a8b75fb4924e7f83430c0c71">llvm::MachO::mapToSupportedOSVersion</a>.</p>

</div>
</div>

### getSubArch {#a2f6aa922f9f6991e7d8aecb147e08fd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubArchType llvm::Triple::getSubArch ()</td>
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

<p>get the parsed subarchitecture type for this triple.</p>

<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>Referenced by <a href="#a13e7af62cc56f460209e36190829d78c">get32BitArchVariant</a>, <a href="#a424c4dc4d08741fa4615cc0c4ec956bd">get64BitArchVariant</a>, <a href="#adb7bb8c037a9662d31b148af4efa2a5a">getBigEndianArchVariant</a>, <a href="#a6ac5d7614594ccea16725535d111652a">getDXILVersion</a>, <a href="#a269e50214be37e2963f53f94518a1894">getLittleEndianArchVariant</a>, <a href="#a6e60a7cae0edfa1045ed0e35c9b55088">getVulkanVersion</a>, <a href="#a32dff8f6f7ea462f82443a33fdf1e4ac">isArm64e</a>, <a href="#a8899fb0df47fe32a7e53cf7a054febe4">isArmMClass</a>, <a href="#a0d80f3ca652a8b79e7553951b0cf2f43">isArmT32</a>, <a href="#ae86f9f850769a4896b883b0da1322a51">isCompatibleWith</a>, <a href="#a14aca434442ff741fa55e97ddccd15ed">isWatchABI</a>, <a href="#ac0544a852d0033d3980285dbd1133ac6">isWindowsArm64EC</a> and <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#aedba1742067f82fe193a19daf690cd06">llvm::object::ELFObjectFileBase::setARMSubArch</a>.</p>

</div>
</div>

### getVendor {#ab4d9af9c278219b313508fce336b7d83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VendorType llvm::Triple::getVendor ()</td>
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

<p>Get the parsed vendor type of this triple.</p>

<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#a5a24823d504d2c91c152e69250b2197d">llvm::SubtargetFeatures::getDefaultSubtargetFeatures</a>, <a href="#a9b7155e7913c06217d85f6a7a3250315">getMinimumSupportedOSVersion</a>, <a href="#adab4eb95e1944ffb12f0d9b349782d3b">isAppleMachO</a>, <a href="#ae86f9f850769a4896b883b0da1322a51">isCompatibleWith</a>, <a href="#a17cc069acf48bda2ac7451a56536cb0c">isPS4</a>, <a href="#ad76134ab5457867366f4ed43758bb8d6">isPS5</a> and <a href="#a8605d2bf7adf880652f2a4fe11ca050d">merge</a>.</p>

</div>
</div>

### getVulkanVersion {#a6e60a7cae0edfa1045ed0e35c9b55088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple Triple::getVulkanVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the Vulkan version number from the OSVersion and SPIR-V version (SubArch).</p>


<p>This should only be called with Vulkan SPIR-V triples.</p>


<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1539 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a836d9cba6deced0bb1fa7333ce5afd3a">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::contains</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>, <a href="#a024faa768c9d7b624a68980113f92693">getOSVersion</a>, <a href="#a2f6aa922f9f6991e7d8aecb147e08fd4">getSubArch</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a023f1e73b058ea58dba15516382eed52">NoSubArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aeee38b63a639e89548c0efc74cab3b65">spirv</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a56d1bb97744ae0c6b4a62d7057b8b3c9">SPIRVSubArch_v15</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a4c3a9a3e3252bd79135d70a26bffb83b">SPIRVSubArch_v16</a> and <a href="#a3cfefc755ab656000934f91193afb1cda844b53b7eb8188bdea24d4147b10d2b3">Vulkan</a>.</p>

</div>
</div>

### getWatchOSVersion {#a07060601788098311a70d6e43327cb08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple Triple::getWatchOSVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the version number as with getOSVersion.</p>


<p>This should only be called with WatchOS or generic triples.</p>


<p>Declaration at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1502 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a3cfefc755ab656000934f91193afb1cda0824a8c56de913d60c6f55edc0ac3148">Darwin</a>, <a href="#a3cfefc755ab656000934f91193afb1cda600aa0b72f321a0cdf0e4b3f38b9b6c8">DriverKit</a>, <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>, <a href="#a024faa768c9d7b624a68980113f92693">getOSVersion</a>, <a href="#a3cfefc755ab656000934f91193afb1cdafad6e6763679be1478d9283a7344d243">IOS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075">MacOSX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>, <a href="#a3cfefc755ab656000934f91193afb1cda87a3c8454473c64f6d605ebd757759ad">WatchOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cdabb5225659a201976ce2594df579e3623">XROS</a>.</p>

</div>
</div>

### hasEnvironment {#aee1760b5f339b38a6f711a2794cf0350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::hasEnvironment ()</td>
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

<p>Does this triple have the optional environment (fourth) component?</p>

<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>Reference <a href="#a685d4808dcb1ae5133120d64593d515b">getEnvironmentName</a>.</p>


<p>Referenced by <a href="#ab3500e69a89f930107cd6f067371da4a">setOSName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Direct Component Access

### getArchName {#ad2d9e5a5c22d594a05d4feae337de252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Triple::getArchName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the architecture (first) component of the triple.</p>

<p>Declaration at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1354 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#aa92ad486f7d87701440dd069319134d5">llvm::ARM::getARMCPUForArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a9ae632cfb346b34a2a80a7f70e1ee048">getDXILArchNameFromShaderModel</a>, <a href="#a6ac5d7614594ccea16725535d111652a">getDXILVersion</a>, <a href="#af70f4019638c4a7cccaaad403c25c048">setArch</a>, <a href="#aac154976a48deecf23babdeb1be05d9f">setEnvironmentName</a>, <a href="#a3eaa25de6a989d7332fa6044b3707226">setOSAndEnvironmentName</a>, <a href="#ab3500e69a89f930107cd6f067371da4a">setOSName</a> and <a href="#a3a48b7e3794824f1fa399052765074ff">setVendorName</a>.</p>

</div>
</div>

### getEnvironmentName {#a685d4808dcb1ae5133120d64593d515b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Triple::getEnvironmentName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the optional environment (fourth) component of the triple, or "" if empty.</p>

<p>Declaration at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1369 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>


<p>Referenced by <a href="#ade97ab011dc19854c9886f2c6d8ecc66">getEnvironmentVersionString</a>, <a href="#aee1760b5f339b38a6f711a2794cf0350">hasEnvironment</a> and <a href="#ab3500e69a89f930107cd6f067371da4a">setOSName</a>.</p>

</div>
</div>

### getEnvironmentVersionString {#ade97ab011dc19854c9886f2c6d8ecc66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Triple::getEnvironmentVersionString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the version component of the environment component as a single string (the version after the environment).</p>


<p>For example, "fooos1.2.3" would return "1.2.3".</p>


<p>Declaration at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1390 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a14180977794bfc2a37dbffeef3ca20de">llvm::StringRef::consume_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a83a294111af6d4412163b209725ca556">llvm::StringRef::contains</a>, <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a>, <a href="#a685d4808dcb1ae5133120d64593d515b">getEnvironmentName</a>, <a href="#abb703efa7aa5bddf5875fe8f2517e787">getEnvironmentTypeName</a>, <a href="#a2e265a0d332c3e2db0acf0c7afd4175d">getObjectFormat</a>, <a href="#ada671e44e91b68a18f8a61f12dd1f475">getObjectFormatTypeName</a>, <a href="#a6ad662bdf0613457ae9b81b47f5555b7">str</a> and <a href="#a83e907e55fa50e093caa96a0aff96201af2f88d8b470958614a01866d4714b5a4">UnknownObjectFormat</a>.</p>


<p>Referenced by <a href="#a5ad45f83c98f9639777cb9924cef58fd">getEnvironmentVersion</a>.</p>

</div>
</div>

### getOSAndEnvironmentName {#a9e404426d1eac2b4c19c8986d9d46cb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Triple::getOSAndEnvironmentName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the operating system and optional environment components as a single string (separated by a '-' if the environment component is present).</p>

<p>Declaration at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1375 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>


<p>Referenced by <a href="#a096c1f8d7977e175075e210101627e0b">setArchName</a> and <a href="#a3a48b7e3794824f1fa399052765074ff">setVendorName</a>.</p>

</div>
</div>

### getOSName {#a483bbccede7948c656b0bd339f39218f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Triple::getOSName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the operating system (third) component of the triple.</p>

<p>Declaration at line 473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1363 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>


<p>Referenced by <a href="#a6ac5d7614594ccea16725535d111652a">getDXILVersion</a>, <a href="#a024faa768c9d7b624a68980113f92693">getOSVersion</a> and <a href="#aac154976a48deecf23babdeb1be05d9f">setEnvironmentName</a>.</p>

</div>
</div>

### getTriple {#a7bc9985614536143e793244dfb66028c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::Triple::getTriple ()</td>
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



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#a8f10e936389f0129adc2f5ded44fdd9a">llvm::codegen::createTargetMachineForTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a9a9a7989eeb174879ae8581e33e61824">llvm::TargetRegistry::lookupTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a7ef5bb146eb2c0e3a609a6a169ac4f44">llvm::EngineBuilder::selectTarget</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6d9c43797976f73bdbe0c75995f84865">llvm::SPIRVTranslate</a>.</p>

</div>
</div>

### getVendorName {#a062f684a024e13d7280e178c95668678}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Triple::getVendorName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the vendor (second) component of the triple.</p>

<p>Declaration at line 470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1358 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>


<p>Referenced by <a href="#a096c1f8d7977e175075e210101627e0b">setArchName</a>, <a href="#aac154976a48deecf23babdeb1be05d9f">setEnvironmentName</a>, <a href="#a3eaa25de6a989d7332fa6044b3707226">setOSAndEnvironmentName</a> and <a href="#ab3500e69a89f930107cd6f067371da4a">setOSName</a>.</p>

</div>
</div>

### str {#a6ad662bdf0613457ae9b81b47f5555b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::Triple::str ()</td>
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



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>Referenced by <a href="#ade97ab011dc19854c9886f2c6d8ecc66">getEnvironmentVersionString</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#ab5019ff9e3502f422f3d8668201f5756">llvm::object::ELFObjectFileBase::getPltEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#aab375071f641a086c0d7067635ccd3dc">llvm::sys::getProcessTriple</a>, <a href="#a8605d2bf7adf880652f2a4fe11ca050d">merge</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/gdbjitdebuginforegistrationplugin/#a01913c5e7fe810e72e2526d49ca29636">llvm::orc::GDBJITDebugInfoRegistrationPlugin::modifyPassConfig</a>, <a href="#a472091dc314efebea60a6c5cff416cc9">setEnvironment</a>, <a href="#a0e2cea374a7428eb1b5ec87ef774e552">setObjectFormat</a>, <a href="#a3a8e516b5874b78eb8bc72e644d62ae5">Triple</a>, <a href="#a2f144736db0877eaef0c6904afee0187">Triple</a> and <a href="#a5795a74557bb339afa955660ecb76247">Triple</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Convenience Predicates

### getArchPointerBitWidth {#a261b9412ba2231505fc5d6ffa7d3a01a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Triple::getArchPointerBitWidth ()</td>
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

<p>Returns the pointer width of this architecture.</p>

<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a> and <a href="#a261b9412ba2231505fc5d6ffa7d3a01a">getArchPointerBitWidth</a>.</p>


<p>Referenced by <a href="#a261b9412ba2231505fc5d6ffa7d3a01a">getArchPointerBitWidth</a>, <a href="#adb3675c020f17151a02604b14c8cdb77">isArch16Bit</a>, <a href="#ae11d6e273225164d9da0c6cad55e093d">isArch32Bit</a> and <a href="#a9e0d7431e635bbbf753602d214d89f0e">isArch64Bit</a>.</p>

</div>
</div>

### getArchPointerBitWidth {#ac338ba44be9ddbf09201b91cc7718985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Triple::getArchPointerBitWidth (<a href="#a547abd13f7a3c063aa72c8192a868154">llvm::Triple::ArchType</a> Arch)</td>
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

<p>Returns the pointer width of this architecture.</p>

<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1641 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">aarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">aarch64_32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">aarch64_be</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">amdgcn</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5ea1b051c09d0127f2d90e0ad6b487df">amdil</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ade794c636782fc46854cb047c40c164b">amdil64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aed5f38c6bd089f09c02aae8072ceb514">arc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">arm</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af65ab1964be676bea302940a45765021">armeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9b780628857be980e628bf44ae7dce56">avr</a>, <a href="#a547abd13f7a3c063aa72c8192a868154abccdd747b05d7cfff6ae937ffdf5ba03">bpfeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a83d003d0efa0cd997646dc0343d7093f">bpfel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a21a4eb647191d4bd084ffdd749dd9100">csky</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ca957896440ddfeeedda9c05723c150">dxil</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5770b66a2436004885ac116a8ac357d5">hexagon</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aca408a723390395eeaa343d8f1e307c4">hsail</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a74533b62667da81390b35d2a47709458">hsail64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5c48161b8fa1243dfab0169510c72bb1">kalimba</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8ccdc49befcb57d683a4ed2025a7f60d">lanai</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0c64155961d19dceb44b43f5a9992d1a">loongarch32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">loongarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae3dbf1f961e0618ea793bc9c099b932a">m68k</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">mips</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">mips64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">mips64el</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">mipsel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a752f0f4d07cf7dcdbe539a95dfe4cbff">msp430</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae06ff88d5da98b63a6b4397fcb7a6050">nvptx</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a92ac53f0fca7e6c3f4e56a2d4903b9ae">nvptx64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">ppc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">ppc64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">ppc64le</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">ppcle</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a060ea888d89f5d59a5743118e429296f">r600</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a863d4793e08f6a5a3ca20149b3e7a85d">renderscript32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a1c43e5f860c9e21dab6fcfc65f93945d">renderscript64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae84559483d0c0f2bddc802ce6f76dd8b">riscv32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08">riscv64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a396b3f1df93fc8cb904b66759a0d1a96">shave</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ebafd1adc05a751215ae959f2891752">sparc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a069fe14c1b6db6a31124817f2e57c954">sparcel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a34e8fe940082d534b3957f06616c8227">sparcv9</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a475e7f13c36b181edba29cfcca212def">spir</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5973589725994222a16112b960c74323">spir64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aeee38b63a639e89548c0efc74cab3b65">spirv</a>, <a href="#a547abd13f7a3c063aa72c8192a868154afc429c7efea3699ead2afe26b7db09df">spirv32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae0a08d9852914cec82b405e32e87fbdc">spirv64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">systemz</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ad7837c42372169017a6e5ff3eaa42d1d">tce</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8f07c386f3b82ef15a54318946248f96">tcele</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">thumb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a038a23cbd1756bf797c083c48229dcfd">thumbeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">UnknownArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a419abb6aa1b60e8d534b06311c1e553c">ve</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ac0478f40eaacc5f340e93827756e7a33">wasm32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ad6b7ed7027706d2960e771c6374025b1">wasm64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">x86</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">x86_64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a1e3f00d3a8c8c59f0f95fd80f1d3ba53">xcore</a> and <a href="#a547abd13f7a3c063aa72c8192a868154ab9cc677b26266a0658a4f6feb4ee0bdc">xtensa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#a983c712b48551572f722178a15e95d27">llvm::jitlink::LinkGraph::LinkGraph</a>.</p>

</div>
</div>

### getTrampolineSize {#a619b009238bd7e0a7bb68afe88f2d2fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Triple::getTrampolineSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the trampoline size in bytes for this configuration.</p>

<p>Declaration at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1714 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">aarch64</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a898af817f450422b11443c35c99e64da">isOSLinux</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">ppc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">ppc64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">ppc64le</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">ppcle</a>.</p>

</div>
</div>

### hasDefaultDataSections {#a553e5eede76e94cc97f728aee36cec71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::hasDefaultDataSections ()</td>
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

<p>Tests whether the target uses -data-sections as default.</p>

<p>Definition at line 1131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a804d3966ad6c4daafeb8a7ae31b8ae2d">isOSBinFormatXCOFF</a> and <a href="#acf7f07dbe7dd1f7edd291b75005280bb">isWasm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#ac754b19265fec508188376da454f57f9">llvm::codegen::InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### hasDefaultEmulatedTLS {#ade012f998cea3bc03f6da0b08d422e6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::hasDefaultEmulatedTLS ()</td>
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

<p>Tests whether the target uses emulated TLS as default.</p>


<p>Note: Android API level 29 (10) introduced <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> TLS.</p>


<p>Definition at line 1121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a3f3873f607a36e40241082727fef44db">isAndroid</a>, <a href="#a13b920f74d7ae331cfd2740a790de541">isAndroidVersionLT</a>, <a href="#a6b2d28c3c85d4b6b274d2d3efbe0afff">isOHOSFamily</a>, <a href="#a6e54a3851d12ab87ef42ebff942bac13">isOSOpenBSD</a> and <a href="#aa0fd88c696cfbb5c2648fe705dcdef5c">isWindowsCygwinEnvironment</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#ac754b19265fec508188376da454f57f9">llvm::codegen::InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### hasDefaultTLSDESC {#a3f39ef170cc0043edb23a89216122e18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::hasDefaultTLSDESC ()</td>
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

<p>True if the target supports both general-dynamic and TLSDESC, and TLSDESC is enabled by default.</p>

<p>Definition at line 1128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a3f3873f607a36e40241082727fef44db">isAndroid</a> and <a href="#a64b2600935100a4be30d8a364609e427">isRISCV64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#ac754b19265fec508188376da454f57f9">llvm::codegen::InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### hasDLLImportExport {#ab893338da73c247a9d4f09038f7f80fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::hasDLLImportExport ()</td>
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

<p>Tests if the environment supports dllimport/export annotations.</p>

<p>Definition at line 1136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a7736bfc4c1afef875ecf02f2a7701fe3">isOSWindows</a> and <a href="#acd9044b8fc48fe6073b88c278aa12d28">isPS</a>.</p>

</div>
</div>

### isAArch64 {#ad953e410aea43848740978d9a6529a82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isAArch64 ()</td>
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

<p>Tests whether the target is <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> (little and big endian).</p>

<p>Definition at line 954 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">aarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">aarch64_32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">aarch64_be</a> and <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#abb08ae2f213bc5b87540413de9b095a2">CreateVarArgHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/entryexitinstrumenter-cpp/#afaedc942c49991373fe6f32bc580b29b">insertCall</a>, <a href="#a2ec13d6660c3676bc8f76c8b7f14f3e8">isAArch64</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284276bdba816c71f6c16ee08e842b41">llvm::FastISel::selectXRayCustomEvent</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a8c80b7d55789b6712c22642d4f94b90d">llvm::FastISel::selectXRayTypedEvent</a>.</p>

</div>
</div>

### isAArch64 {#a2ec13d6660c3676bc8f76c8b7f14f3e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isAArch64 (int PointerWidth)</td>
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

<p>Tests whether the target is <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> and pointers are the size specified by <span class="doxyComputerOutput">PointerWidth</span>.</p>

<p>Definition at line 961 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">aarch64_32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a0a05a130bb4b1c97244ff98d64e0de5d">GNUILP32</a> and <a href="#ad953e410aea43848740978d9a6529a82">isAArch64</a>.</p>

</div>
</div>

### isABIN32 {#a47bfd723026a27a754135ac44f10b9b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isABIN32 ()</td>
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



<p>Definition at line 1080 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a75fa362b8315ce952fde83ff09a4c599">GNUABIN32</a> and <a href="#a1778f5c464f88710033f7e11e84a9324a07818ec9990bfc4675291f2235ab6e8b">MuslABIN32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a>.</p>

</div>
</div>

### isAMDGCN {#a92da6cf2a6b4ce43d5c5e4ef110511aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isAMDGCN ()</td>
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

<p>Tests whether the target is AMDGCN.</p>

<p>Definition at line 886 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">amdgcn</a> and <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>.</p>

</div>
</div>

### isAMDGPU {#a9318bd992483581cc335e1a33782ea45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isAMDGPU ()</td>
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



<p>Definition at line 888 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">amdgcn</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a060ea888d89f5d59a5743118e429296f">r600</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a6f6cda42b5be79b59179a5ca1a3e7bfa">llvm::object::ObjectFile::makeTriple</a>.</p>

</div>
</div>

### isAndroid {#a3f3873f607a36e40241082727fef44db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isAndroid ()</td>
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

<p>Tests whether the target is Android.</p>

<p>Definition at line 803 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a1778f5c464f88710033f7e11e84a9324a0ceb06180ab5fc86e9ad27563b538439">Android</a> and <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a>, <a href="#ade012f998cea3bc03f6da0b08d422e6c">hasDefaultEmulatedTLS</a>, <a href="#a3f39ef170cc0043edb23a89216122e18">hasDefaultTLSDESC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#aaf395b1362beab9f5199bd2094f3d19c">hasStackGuardSlotTLS</a>, <a href="#a13b920f74d7ae331cfd2740a790de541">isAndroidVersionLT</a>, <a href="#ac517c6287b37ff0764afbb97f2a56b51">isOSGlibc</a> and <a href="#a38835c05d2e959d03033c304cd94a1b1">isTargetEHABICompatible</a>.</p>

</div>
</div>

### isAndroidVersionLT {#a13b920f74d7ae331cfd2740a790de541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isAndroidVersionLT (unsigned Major)</td>
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



<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ad45f83c98f9639777cb9924cef58fd">getEnvironmentVersion</a>, <a href="#a3f3873f607a36e40241082727fef44db">isAndroid</a>, <a href="#a9e0d7431e635bbbf753602d214d89f0e">isArch64Bit</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a>, <a href="#ade012f998cea3bc03f6da0b08d422e6c">hasDefaultEmulatedTLS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#aaf395b1362beab9f5199bd2094f3d19c">hasStackGuardSlotTLS</a>.</p>

</div>
</div>

### isAppleMachO {#adab4eb95e1944ffb12f0d9b349782d3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isAppleMachO ()</td>
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

<p>Is this an Apple <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> triple.</p>

<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a96fe35195867c94aef1adf2ad0e20eeca674d908c8b0ebe1880f8c8d651eda9e2">Apple</a>, <a href="#ab4d9af9c278219b313508fce336b7d83">getVendor</a> and <a href="#a444e46ff0a17a6c9480eb151bd42c9bc">isOSBinFormatMachO</a>.</p>

</div>
</div>

### isArch16Bit {#adb3675c020f17151a02604b14c8cdb77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Triple::isArch16Bit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the architecture is 16-bit.</p>


<p>Note that this tests for 16-bit pointer width, and nothing else.</p>


<p>Declaration at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1742 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a> and <a href="#a261b9412ba2231505fc5d6ffa7d3a01a">getArchPointerBitWidth</a>.</p>

</div>
</div>

### isArch32Bit {#ae11d6e273225164d9da0c6cad55e093d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Triple::isArch32Bit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the architecture is 32-bit.</p>


<p>Note that this tests for 32-bit pointer width, and nothing else.</p>


<p>Declaration at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1738 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a> and <a href="#a261b9412ba2231505fc5d6ffa7d3a01a">getArchPointerBitWidth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sys/#aab375071f641a086c0d7067635ccd3dc">llvm::sys::getProcessTriple</a>.</p>

</div>
</div>

### isArch64Bit {#a9e0d7431e635bbbf753602d214d89f0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Triple::isArch64Bit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the architecture is 64-bit.</p>


<p>Note that this tests for 64-bit pointer width, and nothing else. Note that we intentionally expose only three predicates, 64-bit, 32-bit, and 16-bit. The inner details of pointer width for particular architectures is not summed up in the triple, and so only a coarse grained predicate system is provided.</p>


<p>Declaration at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1734 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a> and <a href="#a261b9412ba2231505fc5d6ffa7d3a01a">getArchPointerBitWidth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#a7227d9ecc33b8ed7a50b0d4341448c6c">calculateCXXStateNumbers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a33df8ca13cb8bb9e37d1f43b202aef7f">llvm::WebAssembly::getOrCreateFunctionTableSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#aab375071f641a086c0d7067635ccd3dc">llvm::sys::getProcessTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/object/irobjectfile/#a2b78a9dc71e54e2032c3578f48910a76">llvm::object::IRObjectFile::is64Bit</a>, <a href="#a13b920f74d7ae331cfd2740a790de541">isAndroidVersionLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#aac98d18ebaf02ce89cd8783f59aad2d0">llvm::ifs::parseTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a1d6e16608b64f29f9a4d1483507317b5">llvm::coro::BaseCloner::salvageDebugInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a49ae9dcb1b15c8bd79c384ddf3956db8">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::shouldBuildRelLookupTables</a>.</p>

</div>
</div>

### isARM {#a846115743c5cbbf80216168ad22f906c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isARM ()</td>
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

<p>Tests whether the target is <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> (little and big endian).</p>

<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">arm</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af65ab1964be676bea302940a45765021">armeb</a> and <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#abb08ae2f213bc5b87540413de9b095a2">CreateVarArgHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a> and <a href="#a38835c05d2e959d03033c304cd94a1b1">isTargetEHABICompatible</a>.</p>

</div>
</div>

### isArm64e {#a32dff8f6f7ea462f82443a33fdf1e4ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isArm64e ()</td>
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

<p>Tests whether the target is the Apple "arm64e" <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> subarch.</p>

<p>Definition at line 1074 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">aarch64</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a68fc64acd599f1efceab58c5b1c948c1">AArch64SubArch_arm64e</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a> and <a href="#a2f6aa922f9f6991e7d8aecb147e08fd4">getSubArch</a>.</p>


<p>Referenced by <a href="#a9b7155e7913c06217d85f6a7a3250315">getMinimumSupportedOSVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a7d269a83a714b7924ac1d67e52655c73">llvm::lto::getThinLTODefaultCPU</a>.</p>

</div>
</div>

### isArmMClass {#a8899fb0df47fe32a7e53cf7a054febe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isArmMClass ()</td>
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

<p>Tests whether the target is an M-class.</p>

<p>Definition at line 939 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a9ffca842bbaefcf99484f59a83b618d4adcfb053d1ad63024466047a1c6a92ff3">ARMSubArch_v6m</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4ab8efff655ba87c9dfdd350b51a3d4345">ARMSubArch_v7em</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a56d9342dc07ff0e1a21a3906fe31957c">ARMSubArch_v7m</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4ac0e610ea380b0a0ebb52353ed1a0b1cd">ARMSubArch_v8_1m_mainline</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a782e22ec2166acb2925666b1fdcf87be">ARMSubArch_v8m_baseline</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a0f762073e648e99a9513ac450cae6504">ARMSubArch_v8m_mainline</a> and <a href="#a2f6aa922f9f6991e7d8aecb147e08fd4">getSubArch</a>.</p>

</div>
</div>

### isArmT32 {#a0d80f3ca652a8b79e7553951b0cf2f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isArmT32 ()</td>
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

<p>Tests whether the target is T32.</p>

<p>Definition at line 919 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a9ffca842bbaefcf99484f59a83b618d4accd10f70cf09c8a1612e20f13675f06c">ARMSubArch_v4t</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a65a1a4e325bfede2c90fe1a5c6133bb2">ARMSubArch_v5</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4ac7b6c0c4bacdf3e9f70a4d97348fce9e">ARMSubArch_v5te</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a6f712f6f866568eb3e0b2f7aa652fa35">ARMSubArch_v6</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a5e3ffc6475a86a4e2040e08b27dab792">ARMSubArch_v6k</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4adcfb053d1ad63024466047a1c6a92ff3">ARMSubArch_v6m</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a01fcbdd4fbb3ddfc02aeeea9de057404">ARMSubArch_v6t2</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a310c3af47d446eeaea76dd7ce69241f5">ARMSubArch_v7k</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a8c30db3aef5173efcffcfbb21a083a64">ARMSubArch_v7s</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a7688e046378ef49d94118935e9bdc139">ARMSubArch_v7ve</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a782e22ec2166acb2925666b1fdcf87be">ARMSubArch_v8m_baseline</a> and <a href="#a2f6aa922f9f6991e7d8aecb147e08fd4">getSubArch</a>.</p>

</div>
</div>

### isBPF {#a291cf24ece30f33f071b7f62ee0b9ec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isBPF ()</td>
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

<p>Tests whether the target is eBPF.</p>

<p>Definition at line 1092 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154abccdd747b05d7cfff6ae937ffdf5ba03">bpfeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a83d003d0efa0cd997646dc0343d7093f">bpfel</a> and <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#a13fb59a051bd91cde4c307f263ac5e9c">llvm::symbolize::useBTFContext</a>.</p>

</div>
</div>

### isCSKY {#a64f24694a89d710b9a7f59e1f2df0d12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isCSKY ()</td>
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



<p>Definition at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154a21a4eb647191d4bd084ffdd749dd9100">csky</a> and <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>.</p>

</div>
</div>

### isDriverKit {#a1f396e16b49f3277fc279f94a12d03a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isDriverKit ()</td>
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

<p>Is this an Apple DriverKit triple.</p>

<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a3cfefc755ab656000934f91193afb1cda600aa0b72f321a0cdf0e4b3f38b9b6c8">DriverKit</a> and <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a> and <a href="#ab6fdf9b428bc3d57837022121c155cbf">isOSDarwin</a>.</p>

</div>
</div>

### isDXIL {#af8167b32a55564d0d023cdc3bcd5b0b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isDXIL ()</td>
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

<p>Tests whether the target is DXIL.</p>

<p>Definition at line 839 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154a9ca957896440ddfeeedda9c05723c150">dxil</a> and <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>.</p>

</div>
</div>

### isGNUEnvironment {#af9611bb364d25198d356aa20527fcffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isGNUEnvironment ()</td>
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



<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ae6c91532448c0be7978cf1bfcdaa11bb">GNU</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a21e1198b41cc86aafe10fcd5a6ca330b">GNUABI64</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a75fa362b8315ce952fde83ff09a4c599">GNUABIN32</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a73b4a675dd734e1efcab33de0d217a37">GNUEABI</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a699fcd7db202863a2a82143681dadb85">GNUEABIHF</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ae5c77cfc976654fac7f3f50ee1352a8e">GNUEABIHFT64</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a2343e70ca8369c9a61e3e25aa4e08216">GNUEABIT64</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a61ce851e1f60ad25421987629f5ac2c2">GNUF32</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a587bfd81081ee91855e23c7cc05d4487">GNUF64</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a9953bc1a6bb23d4a733faf9afb0df99a">GNUSF</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a648404ce7e68eb5d5a6c60afa8744438">GNUT64</a> and <a href="#a1778f5c464f88710033f7e11e84a9324ab0c4c38b98e3b1482fc1c5afc8649e28">GNUX32</a>.</p>

</div>
</div>

### isHardFloatABI {#a287017c7824dea2df018a3e237cf2b52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isHardFloatABI ()</td>
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

<p>Tests if the target forces hardfloat.</p>

<p>Definition at line 1104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a1778f5c464f88710033f7e11e84a9324af2b02c10c51141fdaa4cb49402e20169">EABIHF</a>, <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a699fcd7db202863a2a82143681dadb85">GNUEABIHF</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ae5c77cfc976654fac7f3f50ee1352a8e">GNUEABIHFT64</a> and <a href="#a1778f5c464f88710033f7e11e84a9324ab711c5b8f1cd078c75864af125d07fef">MuslEABIHF</a>.</p>

</div>
</div>

### isiOS {#ac36bf25c234d956997781778c866808e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isiOS ()</td>
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

<p>Is this an iOS triple.</p>


<p>Note: This identifies tvOS as a variant of iOS. If that ever changes, i.e., if the two operating systems diverge or their version numbers get out of sync, that will need to be changed. watchOS has completely different version numbers so it is not included.</p>


<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>, <a href="#a3cfefc755ab656000934f91193afb1cdafad6e6763679be1478d9283a7344d243">IOS</a> and <a href="#abf440ac7b84052680788f233de6bcdb6">isTvOS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a> and <a href="#ab6fdf9b428bc3d57837022121c155cbf">isOSDarwin</a>.</p>

</div>
</div>

### isKnownWindowsMSVCEnvironment {#af6d6a4d950ccaa3be4ca4ff2f2169090}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isKnownWindowsMSVCEnvironment ()</td>
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

<p>Checks if the environment is MSVC.</p>

<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a>, <a href="#a7736bfc4c1afef875ecf02f2a7701fe3">isOSWindows</a> and <a href="#a1778f5c464f88710033f7e11e84a9324a6d53dbdf9a8b9b1092558cf23f83a95a">MSVC</a>.</p>


<p>Referenced by <a href="#aed5b9fcccfe88a419343c80064d44d74">isWindowsMSVCEnvironment</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp/#a8fe56fea0dcbc78bba2366b7e2918a41">runImpl</a>.</p>

</div>
</div>

### isLoongArch {#afd03ec8096e2f185d677c27da21f922d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isLoongArch ()</td>
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

<p>Tests whether the target is <a href="/web-llvm/docs/api/namespaces/llvm/loongarch">LoongArch</a> (32- and 64-bit).</p>

<p>Definition at line 978 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a93994a01f6ca3fdd3daf286e2712a465">isLoongArch32</a> and <a href="#a66a1a1858e17b6bcfcbbb1d5229d275e">isLoongArch64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/entryexitinstrumenter-cpp/#afaedc942c49991373fe6f32bc580b29b">insertCall</a>.</p>

</div>
</div>

### isLoongArch32 {#a93994a01f6ca3fdd3daf286e2712a465}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isLoongArch32 ()</td>
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

<p>Tests whether the target is 32-bit <a href="/web-llvm/docs/api/namespaces/llvm/loongarch">LoongArch</a>.</p>

<p>Definition at line 972 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a0c64155961d19dceb44b43f5a9992d1a">loongarch32</a>.</p>


<p>Referenced by <a href="#afd03ec8096e2f185d677c27da21f922d">isLoongArch</a>.</p>

</div>
</div>

### isLoongArch64 {#a66a1a1858e17b6bcfcbbb1d5229d275e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isLoongArch64 ()</td>
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

<p>Tests whether the target is 64-bit <a href="/web-llvm/docs/api/namespaces/llvm/loongarch">LoongArch</a>.</p>

<p>Definition at line 975 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">loongarch64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#abb08ae2f213bc5b87540413de9b095a2">CreateVarArgHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a> and <a href="#afd03ec8096e2f185d677c27da21f922d">isLoongArch</a>.</p>

</div>
</div>

### isMacCatalystEnvironment {#ad7328346f2f8d6b9d897608882bc7758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isMacCatalystEnvironment ()</td>
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



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a> and <a href="#a1778f5c464f88710033f7e11e84a9324a0a522a127e133d8cd07fa678e6672695">MacABI</a>.</p>


<p>Referenced by <a href="#a9b7155e7913c06217d85f6a7a3250315">getMinimumSupportedOSVersion</a> and <a href="#a0c3d390e73840644c0bf96d1933b3396">isTargetMachineMac</a>.</p>

</div>
</div>

### isMacOSX {#aa6a7d5d218ef0d2334fe24eaf997bbb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isMacOSX ()</td>
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

<p>Is this a Mac OS X triple.</p>


<p>For legacy reasons, we support both "darwin" and "osx" as OS X triples.</p>


<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a3cfefc755ab656000934f91193afb1cda0824a8c56de913d60c6f55edc0ac3148">Darwin</a>, <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075">MacOSX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a251d6cd85b676ea4be1e4c2c263494db">anonymous{OffloadWrapper.cpp}::createFatbinDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa1789315a3765f97ea5e82e21f4b9e47">llvm::MCStreamer::emitVersionForTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a>, <a href="#a0092ef6558c242caa4916fbd7fd8da34">isMacOSXVersionLT</a>, <a href="#ab6fdf9b428bc3d57837022121c155cbf">isOSDarwin</a> and <a href="#a0c3d390e73840644c0bf96d1933b3396">isTargetMachineMac</a>.</p>

</div>
</div>

### isMacOSXVersionLT {#a0092ef6558c242caa4916fbd7fd8da34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Triple::isMacOSXVersionLT (unsigned Major, unsigned Minor=0, unsigned Micro=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Comparison function for checking OS X version compatibility, which handles supporting skewed version numbering schemes used by the "darwin" triples.</p>

<p>Declaration at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 2103 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>, <a href="#aa6a7d5d218ef0d2334fe24eaf997bbb6">isMacOSX</a>, <a href="#abc7c65abde53e1e420cab20d84d49cbb">isOSVersionLT</a> and <a href="#a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075">MacOSX</a>.</p>

</div>
</div>

### isMIPS {#ac3b16cb8cc0190f3513f6fee6145c63c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isMIPS ()</td>
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

<p>Tests whether the target is MIPS (little and big endian, 32- or 64-bit).</p>

<p>Definition at line 991 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a73717ef7418a714f20be268c55a2c19e">isMIPS32</a> and <a href="#a52f9355613c6f3388d5761349926d835">isMIPS64</a>.</p>

</div>
</div>

### isMIPS32 {#a73717ef7418a714f20be268c55a2c19e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isMIPS32 ()</td>
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

<p>Tests whether the target is MIPS 32-bit (little and big endian).</p>

<p>Definition at line 981 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">mips</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">mipsel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#abb08ae2f213bc5b87540413de9b095a2">CreateVarArgHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a> and <a href="#ac3b16cb8cc0190f3513f6fee6145c63c">isMIPS</a>.</p>

</div>
</div>

### isMIPS64 {#a52f9355613c6f3388d5761349926d835}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isMIPS64 ()</td>
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

<p>Tests whether the target is MIPS 64-bit (little and big endian).</p>

<p>Definition at line 986 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">mips64</a> and <a href="#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">mips64el</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#abb08ae2f213bc5b87540413de9b095a2">CreateVarArgHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a>, <a href="#ac3b16cb8cc0190f3513f6fee6145c63c">isMIPS</a> and <a href="/web-llvm/docs/api/classes/llvm/mipselfmcasminfo/#a8708ca800840e855dc74da7c335cae33">llvm::MipsELFMCAsmInfo::MipsELFMCAsmInfo</a>.</p>

</div>
</div>

### isMusl {#a7bbfb6d92b2d86cf613bc425e5446b00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isMusl ()</td>
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

<p>Tests whether the environment is musl-libc.</p>

<p>Definition at line 818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a>, <a href="#a96c0dd9835688584c4d9121e8be7704f">isOSLiteOS</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a332336ad935952ff734309ce432de6d1">Musl</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a27355a1eadfe9594a7acc5634d54bfc8">MuslABI64</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a07818ec9990bfc4675291f2235ab6e8b">MuslABIN32</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a8a7dd3fc84b97dc5b1a677d60e46df80">MuslEABI</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ab711c5b8f1cd078c75864af125d07fef">MuslEABIHF</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a66008454cd4031dad58b64c0eae7f9e4">MuslF32</a>, <a href="#a1778f5c464f88710033f7e11e84a9324aff5daa73e757da85e8803ea0e323d5b0">MuslSF</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ae2e0845b94acce4ef8966096195201dd">MuslX32</a> and <a href="#a1778f5c464f88710033f7e11e84a9324a582eb6a495698055109b21d02b959c2e">OpenHOS</a>.</p>


<p>Referenced by <a href="#ae08707e2e2afe994828112fbe8a89817">isPPC32SecurePlt</a> and <a href="#a1ab21929777b807678f98c873cdd7c7c">isPPC64ELFv2ABI</a>.</p>

</div>
</div>

### isNVPTX {#a9871d348bbc1e85bd1daacb428238707}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isNVPTX ()</td>
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

<p>Tests whether the target is <a href="/web-llvm/docs/api/namespaces/llvm/nvptx">NVPTX</a> (32- or 64-bit).</p>

<p>Definition at line 881 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae06ff88d5da98b63a6b4397fcb7a6050">nvptx</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a92ac53f0fca7e6c3f4e56a2d4903b9ae">nvptx64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a4b79b6c874e2b55eb4dda2ae96867f84">llvm::offloading::emitOffloadingEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a68d20206b060ac3ad19f416ed5a4899b">llvm::offloading::getOffloadingEntryInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/internalizepass/#a93e7c89b8c8967cd2eeed0555e66d4f2">llvm::InternalizePass::internalizeModule</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a6f6cda42b5be79b59179a5ca1a3e7bfa">llvm::object::ObjectFile::makeTriple</a> and <a href="/web-llvm/docs/api/classes/anonymous-irmover-cpp-/irlinker/#a29e247c718172acd518f8bb0255ff851">anonymous{IRMover.cpp}::IRLinker::run</a>.</p>

</div>
</div>

### isOHOSFamily {#a6b2d28c3c85d4b6b274d2d3efbe0afff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOHOSFamily ()</td>
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

<p>Tests whether the target is OHOS LiteOS default enviroment is also OHOS, but omited on triple.</p>

<p>Definition at line 832 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#ad59e9ffe0d450e94f287c540ad043130">isOpenHOS</a> and <a href="#a96c0dd9835688584c4d9121e8be7704f">isOSLiteOS</a>.</p>


<p>Referenced by <a href="#ade012f998cea3bc03f6da0b08d422e6c">hasDefaultEmulatedTLS</a>.</p>

</div>
</div>

### isOpenHOS {#ad59e9ffe0d450e94f287c540ad043130}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOpenHOS ()</td>
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



<p>Definition at line 834 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a> and <a href="#a1778f5c464f88710033f7e11e84a9324a582eb6a495698055109b21d02b959c2e">OpenHOS</a>.</p>


<p>Referenced by <a href="#a6b2d28c3c85d4b6b274d2d3efbe0afff">isOHOSFamily</a>.</p>

</div>
</div>

### isOSAIX {#a98cf8213993e03f8b57f294bd66cb40c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSAIX ()</td>
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

<p>Tests whether the OS is AIX.</p>

<p>Definition at line 744 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a3cfefc755ab656000934f91193afb1cda55c9e8cff2a0eab89d1b234d419ee93f">AIX</a> and <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a62fefc41d89d22d96ef82c2537da4343">createPPCAsmPrinterPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/entryexitinstrumenter-cpp/#afaedc942c49991373fe6f32bc580b29b">insertCall</a> and <a href="/web-llvm/docs/api/classes/llvm/internalizepass/#a93e7c89b8c8967cd2eeed0555e66d4f2">llvm::InternalizePass::internalizeModule</a>.</p>

</div>
</div>

### isOSBinFormatCOFF {#a6300d761fd69580d711fad99b934950a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSBinFormatCOFF ()</td>
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

<p>Tests whether the OS uses the <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> binary format.</p>

<p>Definition at line 758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a83e907e55fa50e093caa96a0aff96201aa943abc041caa1cc4c074bbf38b76267">COFF</a> and <a href="#a2e265a0d332c3e2db0acf0c7afd4175d">getObjectFormat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp/#ae03bfc95ecd6ac86582ade86cd2711f1">adjustFixupValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#acd2d48bd67d42ac499c2b0acdef4c2c3">llvm::ARMAsmBackend::adjustFixupValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a676b531bfbeddd2a9614c12d21ad4c88">llvm::createAArch64leAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ae215c9475e5b6a8ae5efa8ff60202dfe">createAArch64MCAsmInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af07717de265cdc07e01ca26be29c1a60">llvm::createMipsAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#a278fb00410ab9c2f73d3578f7b4490ff">createMipsObjectTargetStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae35ef2e57b2c31572d967cb78484ffaa">llvm::createX86_32AsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a306674e8951ad0f9c77cda2f70219ab9">llvm::createX86_64AsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a156c0ad16b9a22a06c6502f59f207f2a">llvm::createX86ObjectTargetStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a4b79b6c874e2b55eb4dda2ae96867f84">llvm::offloading::emitOffloadingEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adb745982e84f05a0d48b878d998d47c7">llvm::RISCVTargetLowering::expandIndirectJTBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adfbecc9eaa3da520aafda5f3078baf3f">llvm::X86TargetLowering::expandIndirectJTBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8476d36f91161750b845b56f25cb7c47">llvm::AArch64MCInstLower::GetGlobalValueSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#af023297673da795cc027d7aa8fd62817">llvm::offloading::getOffloadEntryArray</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a18ff6139760982f4640e0ea26da81ba4">llvm::orc::LLJITBuilderState::prepareForConstruction</a>.</p>

</div>
</div>

### isOSBinFormatDXContainer {#a7df3ae0918bd700a9c8507e3b158e06f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSBinFormatDXContainer ()</td>
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

<p>Tests whether the OS uses the DXContainer binary format.</p>

<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a83e907e55fa50e093caa96a0aff96201a382f97aab858a35311f657a88f998a68">DXContainer</a> and <a href="#a2e265a0d332c3e2db0acf0c7afd4175d">getObjectFormat</a>.</p>


<p>Referenced by <a href="#a49a399e1ef632107f1a062a3d22f2118">supportsCOMDAT</a>.</p>

</div>
</div>

### isOSBinFormatELF {#aea6d215256ae43bc9149bf41f2cc7694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSBinFormatELF ()</td>
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

<p>Tests whether the OS uses the <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> binary format.</p>

<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a83e907e55fa50e093caa96a0aff96201a456b64e26b8bcdbd8294689615d8a055">ELF</a> and <a href="#a2e265a0d332c3e2db0acf0c7afd4175d">getObjectFormat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lto/lto/#a0c3e8ed752bc7ef92ccb9edbd4bb014a">llvm::lto::LTO::add</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#acd2d48bd67d42ac499c2b0acdef4c2c3">llvm::ARMAsmBackend::adjustFixupValue</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#af3c010276b401e92a124e50fcef97fe1">llvm::GlobalObject::canIncreaseAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad838b75c8aa824335f1f1642d5d78545">llvm::createAArch64beAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a676b531bfbeddd2a9614c12d21ad4c88">llvm::createAArch64leAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ae215c9475e5b6a8ae5efa8ff60202dfe">createAArch64MCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp/#a8f6ab6658167369fdde830fd3c8d287c">createARMAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmctargetdesc-cpp/#a281fbab0216589c202c46b283aaca393">createLoongArchObjectTargetStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#aeafb06413605da840d52ad76655540e8">createX86MCAsmInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#af023297673da795cc027d7aa8fd62817">llvm::offloading::getOffloadEntryArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp/#a94b61556b849102cdcace07d0a404434">hasELFSignedGOTHelper</a>, <a href="#a38835c05d2e959d03033c304cd94a1b1">isTargetEHABICompatible</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a18ff6139760982f4640e0ea26da81ba4">llvm::orc::LLJITBuilderState::prepareForConstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp/#a8fe56fea0dcbc78bba2366b7e2918a41">runImpl</a>.</p>

</div>
</div>

### isOSBinFormatGOFF {#a388a623b8ab44f9d44d0525b548fcff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSBinFormatGOFF ()</td>
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

<p>Tests whether the OS uses the <a href="/web-llvm/docs/api/namespaces/llvm/goff">GOFF</a> binary format.</p>

<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a2e265a0d332c3e2db0acf0c7afd4175d">getObjectFormat</a> and <a href="#a83e907e55fa50e093caa96a0aff96201a7d71851eea2209e547ae06c9c03768f5">GOFF</a>.</p>

</div>
</div>

### isOSBinFormatMachO {#a444e46ff0a17a6c9480eb151bd42c9bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSBinFormatMachO ()</td>
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

<p>Tests whether the environment is <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a>.</p>

<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a2e265a0d332c3e2db0acf0c7afd4175d">getObjectFormat</a> and <a href="#a83e907e55fa50e093caa96a0aff96201a2ed78f59e2d35011e1d1ed0ad96cf411">MachO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a676b531bfbeddd2a9614c12d21ad4c88">llvm::createAArch64leAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ae215c9475e5b6a8ae5efa8ff60202dfe">createAArch64MCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#af517e546ece4970a718601f99698bb82">createARMMCAsmInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae35ef2e57b2c31572d967cb78484ffaa">llvm::createX86_32AsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a306674e8951ad0f9c77cda2f70219ab9">llvm::createX86_64AsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#aeafb06413605da840d52ad76655540e8">createX86MCAsmInfo</a>, <a href="#adab4eb95e1944ffb12f0d9b349782d3b">isAppleMachO</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/ehframeregistrationplugin/#af93ceaebd60183ac320cd5927e2e3f81">llvm::orc::EHFrameRegistrationPlugin::modifyPassConfig</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmergeimpl/#a9fbe2dcb11cb3bb78be4d97f388b0c5d">anonymous{GlobalMerge.cpp}::GlobalMergeImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a392f906e72c6fa022d871e028e6f34b9">llvm::orc::LLJIT::setUpGenericLLVMIRPlatform</a> and <a href="#a49a399e1ef632107f1a062a3d22f2118">supportsCOMDAT</a>.</p>

</div>
</div>

### isOSBinFormatWasm {#a1e1c6e3713e5c441d358239f9fac89a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSBinFormatWasm ()</td>
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

<p>Tests whether the OS uses the Wasm binary format.</p>

<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a2e265a0d332c3e2db0acf0c7afd4175d">getObjectFormat</a> and <a href="#a83e907e55fa50e093caa96a0aff96201a660d4029da29691e97daf8c8aabb1ffb">Wasm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/internalizepass/#a93e7c89b8c8967cd2eeed0555e66d4f2">llvm::InternalizePass::internalizeModule</a>.</p>

</div>
</div>

### isOSBinFormatXCOFF {#a804d3966ad6c4daafeb8a7ae31b8ae2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSBinFormatXCOFF ()</td>
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

<p>Tests whether the OS uses the <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> binary format.</p>

<p>Definition at line 776 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a2e265a0d332c3e2db0acf0c7afd4175d">getObjectFormat</a> and <a href="#a83e907e55fa50e093caa96a0aff96201a1f7d761ca747e66d2ac0caa0d54b1824">XCOFF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalobject/#af3c010276b401e92a124e50fcef97fe1">llvm::GlobalObject::canIncreaseAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#ac87ba800a84c083b0ff262ecb6b7f2a4">createPPCMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#ab23c37279d90814b87d6c8ab25b43d0b">emitGlobalConstantImpl</a>, <a href="#a553e5eede76e94cc97f728aee36cec71">hasDefaultDataSections</a> and <a href="#a49a399e1ef632107f1a062a3d22f2118">supportsCOMDAT</a>.</p>

</div>
</div>

### isOSCygMing {#a145fccafbd4d3bb9ff459092d5a5616b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSCygMing ()</td>
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

<p>Tests for either Cygwin or MinGW OS.</p>

<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#aa0fd88c696cfbb5c2648fe705dcdef5c">isWindowsCygwinEnvironment</a> and <a href="#a398f3f1f57fae295ca4ae75a3b56fa59">isWindowsGNUEnvironment</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#aeafb06413605da840d52ad76655540e8">createX86MCAsmInfo</a>.</p>

</div>
</div>

### isOSDarwin {#ab6fdf9b428bc3d57837022121c155cbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSDarwin ()</td>
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

<p>Is this a "Darwin" OS (macOS, iOS, tvOS, watchOS, XROS, or DriverKit).</p>

<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a1f396e16b49f3277fc279f94a12d03a5">isDriverKit</a>, <a href="#ac36bf25c234d956997781778c866808e">isiOS</a>, <a href="#aa6a7d5d218ef0d2334fe24eaf997bbb6">isMacOSX</a>, <a href="#ac2eddca981f187178a53969d88465b4c">isWatchOS</a> and <a href="#aaba295444f638da56e58010cf7fb091d">isXROS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armmcasminfodarwin/#a9431bd9edb8400058b9caccf2c38f21e">llvm::ARMMCAsmInfoDarwin::ARMMCAsmInfoDarwin</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#acf3eb0f1888bed0ff1df0667cd1036aa">ContainsProtectableArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#af517e546ece4970a718601f99698bb82">createARMMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a8d5210bd68a86582390a6fbf1f57e319">llvm::TargetInstrInfo::duplicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a7d269a83a714b7924ac1d67e52655c73">llvm::lto::getThinLTODefaultCPU</a>, <a href="#a0c3d390e73840644c0bf96d1933b3396">isTargetMachineMac</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a392f906e72c6fa022d871e028e6f34b9">llvm::orc::LLJIT::setUpGenericLLVMIRPlatform</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a49ae9dcb1b15c8bd79c384ddf3956db8">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::shouldBuildRelLookupTables</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a755eb2d2f25e8da3b2d904146e61b1a5">shouldLowerMemFuncForSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a071d371524d9b324ba9c5cc489ee3da6">shouldLowerMemFuncForSize</a> and <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#aa7dba30d4d9162f00367404e06085391">llvm::TailDuplicator::shouldTailDuplicate</a>.</p>

</div>
</div>

### isOSDragonFly {#a03aa5e23acb1aace7f2d2014cd3382ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSDragonFly ()</td>
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



<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a3cfefc755ab656000934f91193afb1cda0e7175bb9a8eea9efd2a5e50b6ca84ab">DragonFly</a> and <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>.</p>

</div>
</div>

### isOSEmscripten {#ac044f740fee04796ffe5ba17fdc3fa0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSEmscripten ()</td>
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

<p>Tests whether the OS is Emscripten.</p>

<p>Definition at line 732 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a3cfefc755ab656000934f91193afb1cdae7c70b9eb6106c04f131eca1e3be44ac">Emscripten</a> and <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a30ad890949cdfd6777919b71f4d09dfe">GetCtorAndDtorPriority</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-memprofiler-cpp-/#a25e178fd0357943af89097c8fc90a29a">anonymous{MemProfiler.cpp}::getCtorAndDtorPriority</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a>.</p>

</div>
</div>

### isOSFreeBSD {#aa98a01c1d72fde0f87823d204dc98334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSFreeBSD ()</td>
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



<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a3cfefc755ab656000934f91193afb1cda64fc6929b84f845ced55d3313ebcf423">FreeBSD</a> and <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2793bce814c8f8c6fc2f41d4156a4ebb">llvm::TargetLoweringObjectFileELF::Initialize</a>.</p>

</div>
</div>

### isOSFuchsia {#ae891092a64f3b737dcba557a8450587c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSFuchsia ()</td>
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



<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a3cfefc755ab656000934f91193afb1cdaad44ff9454db9e8eb2e38d964f0345b7">Fuchsia</a> and <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#aaf395b1362beab9f5199bd2094f3d19c">hasStackGuardSlotTLS</a>.</p>

</div>
</div>

### isOSGlibc {#ac517c6287b37ff0764afbb97f2a56b51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSGlibc ()</td>
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

<p>Tests whether the OS uses glibc.</p>

<p>Definition at line 737 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>, <a href="#a3cfefc755ab656000934f91193afb1cdaf17d175b40b8e7ceedc92aea3929eb27">Hurd</a>, <a href="#a3f3873f607a36e40241082727fef44db">isAndroid</a>, <a href="#a3cfefc755ab656000934f91193afb1cda6506444610ddf1a927cf919508b2ea1b">KFreeBSD</a> and <a href="#a3cfefc755ab656000934f91193afb1cda76d4dd8dc67e3a11d975743f6d63a9df">Linux</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#aaf395b1362beab9f5199bd2094f3d19c">hasStackGuardSlotTLS</a>.</p>

</div>
</div>

### isOSHaiku {#af70af5dfe0ad906d51c7ca09d13a3e2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSHaiku ()</td>
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

<p>Tests whether the OS is Haiku.</p>

<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cda55732429424dd801e57c7c667a8d4217">Haiku</a>.</p>

</div>
</div>

### isOSHurd {#a26f50a368caaea38084bc9b40769ade1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSHurd ()</td>
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

<p>Tests whether the OS is Hurd.</p>

<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cdaf17d175b40b8e7ceedc92aea3929eb27">Hurd</a>.</p>

</div>
</div>

### isOSIAMCU {#ad3d505c1a9bc7380a73561d84d063ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSIAMCU ()</td>
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



<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a3cfefc755ab656000934f91193afb1cdaea39dbcca2c32c044d958aceb371bb13">ELFIAMCU</a> and <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae35ef2e57b2c31572d967cb78484ffaa">llvm::createX86_32AsmBackend</a>.</p>

</div>
</div>

### isOSKFreeBSD {#a57ba86412d0c09795efe03bd06b8dba1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSKFreeBSD ()</td>
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

<p>Tests whether the OS is kFreeBSD.</p>

<p>Definition at line 717 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cda6506444610ddf1a927cf919508b2ea1b">KFreeBSD</a>.</p>

</div>
</div>

### isOSLinux {#a898af817f450422b11443c35c99e64da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSLinux ()</td>
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

<p>Tests whether the OS is Linux.</p>

<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cda76d4dd8dc67e3a11d975743f6d63a9df">Linux</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a> and <a href="#a619b009238bd7e0a7bb68afe88f2d2fd">getTrampolineSize</a>.</p>

</div>
</div>

### isOSLiteOS {#a96c0dd9835688584c4d9121e8be7704f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSLiteOS ()</td>
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



<p>Definition at line 836 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cdaf7d25a9254177b6890fd8c115503014d">LiteOS</a>.</p>


<p>Referenced by <a href="#a7bbfb6d92b2d86cf613bc425e5446b00">isMusl</a> and <a href="#a6b2d28c3c85d4b6b274d2d3efbe0afff">isOHOSFamily</a>.</p>

</div>
</div>

### isOSMSVCRT {#a438b0136b755625f50ea227cc19e5ad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSMSVCRT ()</td>
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

<p>Is this a "Windows" OS targeting a "MSVCRT.dll" environment.</p>

<p>Definition at line 701 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a398f3f1f57fae295ca4ae75a3b56fa59">isWindowsGNUEnvironment</a>, <a href="#afdd0d3d27ef11fd6ad21da63c3979d77">isWindowsItaniumEnvironment</a> and <a href="#aed5b9fcccfe88a419343c80064d44d74">isWindowsMSVCEnvironment</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp/#a494dabe67c8e93868fed4e59fbd49150">computeBytesPoppedByCalleeForSRet</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#aa546b9d95bbcbc4590bbd3bfdafcf9c0">hasCalleePopSRet</a>.</p>

</div>
</div>

### isOSNaCl {#a0dd94ab3854e0421e795ce04ee3babf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSNaCl ()</td>
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

<p>Tests whether the OS is NaCl (Native Client)</p>

<p>Definition at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cdaae17c480f3a0e37421e04400dca90d1b">NaCl</a>.</p>

</div>
</div>

### isOSNetBSD {#a3d98f3cc4fe2adddfa98dc0dbee55bdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSNetBSD ()</td>
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



<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cdad10d236fcf52bdbf36bd6b401ca9e427">NetBSD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a>.</p>

</div>
</div>

### isOSOpenBSD {#a6e54a3851d12ab87ef42ebff942bac13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSOpenBSD ()</td>
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



<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cda13c01bda5d01cb2264a0cebe7b411c54">OpenBSD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#a826f32ce82e4b2605718fedddba8a055">CreateFailBB</a> and <a href="#ade012f998cea3bc03f6da0b08d422e6c">hasDefaultEmulatedTLS</a>.</p>

</div>
</div>

### isOSSerenity {#a6b1293b8705b0bd5ae5c783029399016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSSerenity ()</td>
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



<p>Definition at line 748 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cda3abcbc3caa438ea915121cdf3d373aae">Serenity</a>.</p>

</div>
</div>

### isOSSolaris {#a565d07b44e55cbff02db88c1d5cf3cb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSSolaris ()</td>
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



<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cdac44628c2fbd9505dc608a330838fccce">Solaris</a>.</p>

</div>
</div>

### isOSUnknown {#a70cdd4fe5787c4383db8bbd21570f062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSUnknown ()</td>
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



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cda4b110a50637320a1a0db33999b809ddd">UnknownOS</a>.</p>

</div>
</div>

### isOSVersionLT {#abc7c65abde53e1e420cab20d84d49cbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSVersionLT (unsigned Major, unsigned Minor=0, unsigned Micro=0)</td>
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

<p>Helper function for doing comparisons against version numbers included in the target triple.</p>

<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>Reference <a href="#a024faa768c9d7b624a68980113f92693">getOSVersion</a>.</p>


<p>Referenced by <a href="#a0092ef6558c242caa4916fbd7fd8da34">isMacOSXVersionLT</a>.</p>

</div>
</div>

### isOSVersionLT {#a5fa1f16bd79509b687e8c593a048a225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSVersionLT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; Other)</td>
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



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a024faa768c9d7b624a68980113f92693">getOSVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a15410866a30d89459a6f99034202e475">Triple</a>.</p>

</div>
</div>

### isOSWASI {#a1bcb02d757ae9d46b7720d607ce67d76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSWASI ()</td>
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

<p>Tests whether the OS is WASI.</p>

<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cdab4b12e4f268dff8ead7f9194ee8da04b">WASI</a>.</p>

</div>
</div>

### isOSWindows {#a7736bfc4c1afef875ecf02f2a7701fe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSWindows ()</td>
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

<p>Tests whether the OS is Windows.</p>

<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cdafd0c0a465dca43ad44f79806a226a1ae">Win32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp/#a8f6ab6658167369fdde830fd3c8d287c">createARMAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#af517e546ece4970a718601f99698bb82">createARMMCAsmInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af07717de265cdc07e01ca26be29c1a60">llvm::createMipsAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae35ef2e57b2c31572d967cb78484ffaa">llvm::createX86_32AsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a306674e8951ad0f9c77cda2f70219ab9">llvm::createX86_64AsmBackend</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8476d36f91161750b845b56f25cb7c47">llvm::AArch64MCInstLower::GetGlobalValueSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a>, <a href="#ab893338da73c247a9d4f09038f7f80fe">hasDLLImportExport</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#ad7c5a4356eb729fe374f917da7435a12">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardCheck</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a6817bdede4df5251b8422f22617be51f">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardDispatch</a>, <a href="#af6d6a4d950ccaa3be4ca4ff2f2169090">isKnownWindowsMSVCEnvironment</a>, <a href="#a7c38226b3063da1cb0bd1ce44a31b48f">isOSWindowsOrUEFI</a>, <a href="#a4aff54e7e4562b21d5762a6ca406f9f7">isWindowsCoreCLREnvironment</a>, <a href="#aa0fd88c696cfbb5c2648fe705dcdef5c">isWindowsCygwinEnvironment</a>, <a href="#a398f3f1f57fae295ca4ae75a3b56fa59">isWindowsGNUEnvironment</a>, <a href="#afdd0d3d27ef11fd6ad21da63c3979d77">isWindowsItaniumEnvironment</a>, <a href="#aed5b9fcccfe88a419343c80064d44d74">isWindowsMSVCEnvironment</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7791efd93b12280fdad994fb6073933d">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp/#a7010c624fdaf139f8efa60219c3b56bf">ShouldSignWithBKey</a>.</p>

</div>
</div>

### isOSWindowsOrUEFI {#a7c38226b3063da1cb0bd1ce44a31b48f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSWindowsOrUEFI ()</td>
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

<p>Tests whether the OS is Windows or UEFI.</p>

<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a7736bfc4c1afef875ecf02f2a7701fe3">isOSWindows</a> and <a href="#a76b2f9ab09b41fed3ffeb43eda2533d8">isUEFI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86mcasminfognucoff/#a962aeeaf657c538ec248271056d017ec">llvm::X86MCAsmInfoGNUCOFF::X86MCAsmInfoGNUCOFF</a>.</p>

</div>
</div>

### isOSzOS {#a6b121909a2e76bd11b0673b0eeb58b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isOSzOS ()</td>
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



<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cdafd36ac5f07b0474e2b5c167ab7158538">ZOS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5e2f30307ffe41c5d4e80899ee135826">llvm::createSystemZMCAsmBackend</a>.</p>

</div>
</div>

### isPPC {#a0338eabc8ab4dff6368bdfae6ec94cbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isPPC ()</td>
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

<p>Tests whether the target is PowerPC (32- or 64-bit LE or BE).</p>

<p>Definition at line 996 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">ppc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">ppc64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">ppc64le</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">ppcle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ac5b407054e7727d04053af9c3f1a5568">llvm::OpenMPIRBuilder::getOpenMPDefaultSimdAlign</a>.</p>

</div>
</div>

### isPPC32 {#a5fbc3fe5e4f1e0f9515cfac36293b1c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isPPC32 ()</td>
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

<p>Tests whether the target is 32-bit PowerPC (little and big endian).</p>

<p>Definition at line 1002 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">ppc</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">ppcle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#abb08ae2f213bc5b87540413de9b095a2">CreateVarArgHelper</a>.</p>

</div>
</div>

### isPPC32SecurePlt {#ae08707e2e2afe994828112fbe8a89817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isPPC32SecurePlt ()</td>
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

<p>Tests whether the target 32-bit PowerPC uses Secure PLT.</p>

<p>Definition at line 1020 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a3cfefc755ab656000934f91193afb1cda64fc6929b84f845ced55d3313ebcf423">FreeBSD</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>, <a href="#ae6bb6cb4330e31951d06537d80c39e62">getOSMajorVersion</a>, <a href="#a024faa768c9d7b624a68980113f92693">getOSVersion</a>, <a href="#a7bbfb6d92b2d86cf613bc425e5446b00">isMusl</a>, <a href="#a3cfefc755ab656000934f91193afb1cdad10d236fcf52bdbf36bd6b401ca9e427">NetBSD</a>, <a href="#a3cfefc755ab656000934f91193afb1cda13c01bda5d01cb2264a0cebe7b411c54">OpenBSD</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">ppc</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">ppcle</a>.</p>

</div>
</div>

### isPPC64 {#ab61d338cbe7892ab484e97c9b0c8c8c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isPPC64 ()</td>
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

<p>Tests whether the target is 64-bit PowerPC (little and big endian).</p>

<p>Definition at line 1007 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">ppc64</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">ppc64le</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#abb08ae2f213bc5b87540413de9b095a2">CreateVarArgHelper</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargpowerpchelper/#a6a7c02af1eb9545e64bdf82e7f7d763e">anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper::finalizeInstrumentation</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargpowerpchelper/#a8e4ae572b54705c019d49eaed31ce04f">anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper::visitCallBase</a>.</p>

</div>
</div>

### isPPC64ELFv2ABI {#a1ab21929777b807678f98c873cdd7c7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isPPC64ELFv2ABI ()</td>
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

<p>Tests whether the target 64-bit PowerPC big endian ABI is ELFv2.</p>

<p>Definition at line 1012 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a3cfefc755ab656000934f91193afb1cda64fc6929b84f845ced55d3313ebcf423">FreeBSD</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>, <a href="#ae6bb6cb4330e31951d06537d80c39e62">getOSMajorVersion</a>, <a href="#a024faa768c9d7b624a68980113f92693">getOSVersion</a>, <a href="#a7bbfb6d92b2d86cf613bc425e5446b00">isMusl</a>, <a href="#a3cfefc755ab656000934f91193afb1cda13c01bda5d01cb2264a0cebe7b411c54">OpenBSD</a> and <a href="#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">ppc64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a18ff6139760982f4640e0ea26da81ba4">llvm::orc::LLJITBuilderState::prepareForConstruction</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargpowerpchelper/#a8e4ae572b54705c019d49eaed31ce04f">anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper::visitCallBase</a>.</p>

</div>
</div>

### isPS {#acd9044b8fc48fe6073b88c278aa12d28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isPS ()</td>
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

<p>Tests whether the target is the PS4 or PS5 platform.</p>

<p>Definition at line 800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a17cc069acf48bda2ac7451a56536cb0c">isPS4</a> and <a href="#ad76134ab5457867366f4ed43758bb8d6">isPS5</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a> and <a href="#ab893338da73c247a9d4f09038f7f80fe">hasDLLImportExport</a>.</p>

</div>
</div>

### isPS4 {#a17cc069acf48bda2ac7451a56536cb0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isPS4 ()</td>
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

<p>Tests whether the target is the PS4 platform.</p>

<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>, <a href="#ab4d9af9c278219b313508fce336b7d83">getVendor</a>, <a href="#a3cfefc755ab656000934f91193afb1cda63d6dc93c7b6ab41ba169620a639bec1">PS4</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eecaf8cf55a2ccb688a02134bd768c9a1a3d">SCEI</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">x86_64</a>.</p>


<p>Referenced by <a href="#acd9044b8fc48fe6073b88c278aa12d28">isPS</a>.</p>

</div>
</div>

### isPS5 {#ad76134ab5457867366f4ed43758bb8d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isPS5 ()</td>
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

<p>Tests whether the target is the PS5 platform.</p>

<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>, <a href="#ab4d9af9c278219b313508fce336b7d83">getVendor</a>, <a href="#a3cfefc755ab656000934f91193afb1cda683700aa7afbff16fe3885d5ad05923c">PS5</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eecaf8cf55a2ccb688a02134bd768c9a1a3d">SCEI</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">x86_64</a>.</p>


<p>Referenced by <a href="#acd9044b8fc48fe6073b88c278aa12d28">isPS</a>.</p>

</div>
</div>

### isRISCV {#a92c6b6260dedf314bf70156000628e80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isRISCV ()</td>
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

<p>Tests whether the target is RISC-V (32- and 64-bit).</p>

<p>Definition at line 1035 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a578c0e35b3e3ed8c73e610a0882a9d6a">isRISCV32</a> and <a href="#a64b2600935100a4be30d8a364609e427">isRISCV64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/entryexitinstrumenter-cpp/#afaedc942c49991373fe6f32bc580b29b">insertCall</a> and <a href="/web-llvm/docs/api/structs/anonymous-xrayinstrumentation-cpp-/xrayinstrumentation/#a4fb91ea8621a93ca73b483592ac6b061">anonymous{XRayInstrumentation.cpp}::XRayInstrumentation::runOnMachineFunction</a>.</p>

</div>
</div>

### isRISCV32 {#a578c0e35b3e3ed8c73e610a0882a9d6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isRISCV32 ()</td>
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

<p>Tests whether the target is 32-bit RISC-V.</p>

<p>Definition at line 1029 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a> and <a href="#a547abd13f7a3c063aa72c8192a868154ae84559483d0c0f2bddc802ce6f76dd8b">riscv32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#abb08ae2f213bc5b87540413de9b095a2">CreateVarArgHelper</a> and <a href="#a92c6b6260dedf314bf70156000628e80">isRISCV</a>.</p>

</div>
</div>

### isRISCV64 {#a64b2600935100a4be30d8a364609e427}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isRISCV64 ()</td>
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

<p>Tests whether the target is 64-bit RISC-V.</p>

<p>Definition at line 1032 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a> and <a href="#a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08">riscv64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#abb08ae2f213bc5b87540413de9b095a2">CreateVarArgHelper</a>, <a href="#a3f39ef170cc0043edb23a89216122e18">hasDefaultTLSDESC</a> and <a href="#a92c6b6260dedf314bf70156000628e80">isRISCV</a>.</p>

</div>
</div>

### isShaderModelOS {#a74c3ac300c06a2c491256534b99b08b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isShaderModelOS ()</td>
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



<p>Definition at line 843 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cdac4081e09efdc53c28fc78e5ca68ea70a">ShaderModel</a>.</p>

</div>
</div>

### isShaderStageEnvironment {#afd88a4e5f804888b864374a454f6d13f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isShaderStageEnvironment ()</td>
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



<p>Definition at line 849 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a1778f5c464f88710033f7e11e84a9324ab926bec66aeb0288525973f203bcb94a">Amplification</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ab73388cc76387a636177ac9e405d0b39">AnyHit</a>, <a href="#a1778f5c464f88710033f7e11e84a9324adf4a58c1d4eb1aeba280a3fc580e9f8d">Callable</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a783d818fcc0a9d1e095674aa7b255082">ClosestHit</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a35a7d7865588f76c4f300fb1f07ee1bc">Compute</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a9250a1f506b7407b838bf0b494f9cd33">Domain</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ade3aad57a34a47654ebeee1a2d4ab960">Geometry</a>, <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ac8bc9b9934c75b722dcdde3b705c0a51">Hull</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ac5ff0a8f8e278b84cdd8518a6e0c67d8">Intersection</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a38ed328b8551b06c5a133e54867110bf">Library</a>, <a href="#a1778f5c464f88710033f7e11e84a9324aa1a97c079fbb80fcd9ab0f5fa24f3025">Mesh</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ad6c99823a0c7477c6412728485bb0fe7">Miss</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a4bd403d91c4535171833f92e0ce36137">Pixel</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a15bc4c083c1cda54e3011297b4bf8351">RayGeneration</a> and <a href="#a1778f5c464f88710033f7e11e84a9324a71b983b2a1bf8a46c5ac7d21de26fb4a">Vertex</a>.</p>

</div>
</div>

### isSimulatorEnvironment {#a6a66d02819186762f85145d632f9f81f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isSimulatorEnvironment ()</td>
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



<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a> and <a href="#a1778f5c464f88710033f7e11e84a9324a587146bd8be66f0980d55ca2664c5642">Simulator</a>.</p>


<p>Referenced by <a href="#a9b7155e7913c06217d85f6a7a3250315">getMinimumSupportedOSVersion</a> and <a href="#a0c3d390e73840644c0bf96d1933b3396">isTargetMachineMac</a>.</p>

</div>
</div>

### isSPARC {#ab61318fe3bda34b9889b7c4293d091be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isSPARC ()</td>
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

<p>Tests whether the target is SPARC.</p>

<p>Definition at line 1046 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a692addc79837dc704398400593123895">isSPARC32</a> and <a href="#aa0e575c51232ced86460d9ae83f96cbc">isSPARC64</a>.</p>

</div>
</div>

### isSPARC32 {#a692addc79837dc704398400593123895}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isSPARC32 ()</td>
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

<p>Tests whether the target is 32-bit SPARC (little and big endian).</p>

<p>Definition at line 1038 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ebafd1adc05a751215ae959f2891752">sparc</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a069fe14c1b6db6a31124817f2e57c954">sparcel</a>.</p>


<p>Referenced by <a href="#ab61318fe3bda34b9889b7c4293d091be">isSPARC</a>.</p>

</div>
</div>

### isSPARC64 {#aa0e575c51232ced86460d9ae83f96cbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isSPARC64 ()</td>
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

<p>Tests whether the target is 64-bit SPARC (big endian).</p>

<p>Definition at line 1043 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a34e8fe940082d534b3957f06616c8227">sparcv9</a>.</p>


<p>Referenced by <a href="#ab61318fe3bda34b9889b7c4293d091be">isSPARC</a> and <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ab74cde0c8282be6c158a967ff13642a3">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::LowerGETPCXAndEmitMCInsts</a>.</p>

</div>
</div>

### isSPIR {#a1c0737f9edc41d1a0ec4b5ec9a7e8b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isSPIR ()</td>
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

<p>Tests whether the target is SPIR (32- or 64-bit).</p>

<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a475e7f13c36b181edba29cfcca212def">spir</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a5973589725994222a16112b960c74323">spir64</a>.</p>


<p>Referenced by <a href="#a4deb097184b76d30b09cfeac681aba19">isSPIROrSPIRV</a>.</p>

</div>
</div>

### isSPIROrSPIRV {#a4deb097184b76d30b09cfeac681aba19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isSPIROrSPIRV ()</td>
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



<p>Definition at line 873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a1c0737f9edc41d1a0ec4b5ec9a7e8b87">isSPIR</a> and <a href="#ad77183da26fd51a168f2cedcd0df3561">isSPIRV</a>.</p>

</div>
</div>

### isSPIRV {#ad77183da26fd51a168f2cedcd0df3561}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isSPIRV ()</td>
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

<p>Tests whether the target is SPIR-V (32/64-bit/Logical).</p>

<p>Definition at line 867 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aeee38b63a639e89548c0efc74cab3b65">spirv</a>, <a href="#a547abd13f7a3c063aa72c8192a868154afc429c7efea3699ead2afe26b7db09df">spirv32</a> and <a href="#a547abd13f7a3c063aa72c8192a868154ae0a08d9852914cec82b405e32e87fbdc">spirv64</a>.</p>


<p>Referenced by <a href="#a4deb097184b76d30b09cfeac681aba19">isSPIROrSPIRV</a>.</p>

</div>
</div>

### isSPIRVLogical {#aba6fc3ce3bf1813201d150730c918d70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isSPIRVLogical ()</td>
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

<p>Tests whether the target is SPIR-V Logical.</p>

<p>Definition at line 876 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a> and <a href="#a547abd13f7a3c063aa72c8192a868154aeee38b63a639e89548c0efc74cab3b65">spirv</a>.</p>

</div>
</div>

### isSystemZ {#ade08dbf7a3d70b46b55c4257b3a536de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isSystemZ ()</td>
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

<p>Tests whether the target is <a href="/web-llvm/docs/api/namespaces/llvm/systemz">SystemZ</a>.</p>

<p>Definition at line 1049 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a> and <a href="#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">systemz</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#abb08ae2f213bc5b87540413de9b095a2">CreateVarArgHelper</a>.</p>

</div>
</div>

### isTargetEHABICompatible {#a38835c05d2e959d03033c304cd94a1b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isTargetEHABICompatible ()</td>
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

<p>Tests whether the target supports the EHABI exception handling standard.</p>

<p>Definition at line 904 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a1778f5c464f88710033f7e11e84a9324a847a953f3f994ab5453f075cea9ca7af">EABI</a>, <a href="#a1778f5c464f88710033f7e11e84a9324af2b02c10c51141fdaa4cb49402e20169">EABIHF</a>, <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a73b4a675dd734e1efcab33de0d217a37">GNUEABI</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a699fcd7db202863a2a82143681dadb85">GNUEABIHF</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ae5c77cfc976654fac7f3f50ee1352a8e">GNUEABIHFT64</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a2343e70ca8369c9a61e3e25aa4e08216">GNUEABIT64</a>, <a href="#a3f3873f607a36e40241082727fef44db">isAndroid</a>, <a href="#a846115743c5cbbf80216168ad22f906c">isARM</a>, <a href="#aea6d215256ae43bc9149bf41f2cc7694">isOSBinFormatELF</a>, <a href="#a17b2679f91f697a4ffe46b872152e25b">isThumb</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a8a7dd3fc84b97dc5b1a677d60e46df80">MuslEABI</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ab711c5b8f1cd078c75864af125d07fef">MuslEABIHF</a> and <a href="#a1778f5c464f88710033f7e11e84a9324a582eb6a495698055109b21d02b959c2e">OpenHOS</a>.</p>

</div>
</div>

### isTargetMachineMac {#a0c3d390e73840644c0bf96d1933b3396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isTargetMachineMac ()</td>
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

<p>Returns true for targets that run on a macOS machine.</p>

<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#ad7328346f2f8d6b9d897608882bc7758">isMacCatalystEnvironment</a>, <a href="#aa6a7d5d218ef0d2334fe24eaf997bbb6">isMacOSX</a>, <a href="#ab6fdf9b428bc3d57837022121c155cbf">isOSDarwin</a> and <a href="#a6a66d02819186762f85145d632f9f81f">isSimulatorEnvironment</a>.</p>

</div>
</div>

### isThumb {#a17b2679f91f697a4ffe46b872152e25b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isThumb ()</td>
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

<p>Tests whether the target is Thumb (little and big endian).</p>

<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">thumb</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a038a23cbd1756bf797c083c48229dcfd">thumbeb</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp/#a8f6ab6658167369fdde830fd3c8d287c">createARMAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a>, <a href="#a38835c05d2e959d03033c304cd94a1b1">isTargetEHABICompatible</a> and <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#aedba1742067f82fe193a19daf690cd06">llvm::object::ELFObjectFileBase::setARMSubArch</a>.</p>

</div>
</div>

### isTime64ABI {#ae09fbe778f8a1f090e6d3fb5175bdb4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isTime64ABI ()</td>
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

<p>Tests if the target forces 64-bit time_t on a 32-bit architecture.</p>

<p>Definition at line 1097 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ae5c77cfc976654fac7f3f50ee1352a8e">GNUEABIHFT64</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a2343e70ca8369c9a61e3e25aa4e08216">GNUEABIT64</a> and <a href="#a1778f5c464f88710033f7e11e84a9324a648404ce7e68eb5d5a6c60afa8744438">GNUT64</a>.</p>

</div>
</div>

### isTvOS {#abf440ac7b84052680788f233de6bcdb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isTvOS ()</td>
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

<p>Is this an Apple tvOS triple.</p>

<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cda2838cf6df0f09591c50d752d46c4350d">TvOS</a>.</p>


<p>Referenced by <a href="#ac36bf25c234d956997781778c866808e">isiOS</a>.</p>

</div>
</div>

### isUEFI {#a76b2f9ab09b41fed3ffeb43eda2533d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isUEFI ()</td>
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

<p>Tests whether the OS is UEFI.</p>

<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cda7af47f8e02ca8bd701e40ba03b2bcd95">UEFI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a306674e8951ad0f9c77cda2f70219ab9">llvm::createX86_64AsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#aeafb06413605da840d52ad76655540e8">createX86MCAsmInfo</a> and <a href="#a7c38226b3063da1cb0bd1ce44a31b48f">isOSWindowsOrUEFI</a>.</p>

</div>
</div>

### isVE {#afeb095611dceaee172b9ab66a9f765ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isVE ()</td>
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

<p>Tests whether the target is <a href="/web-llvm/docs/api/namespaces/llvm/ve">VE</a>.</p>

<p>Definition at line 1059 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a419abb6aa1b60e8d534b06311c1e553c">ve</a>.</p>

</div>
</div>

### isVulkanOS {#ad1a8e844d6b87311c662964dd8826358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isVulkanOS ()</td>
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



<p>Definition at line 847 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cda844b53b7eb8188bdea24d4147b10d2b3">Vulkan</a>.</p>

</div>
</div>

### isWasm {#acf7f07dbe7dd1f7edd291b75005280bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isWasm ()</td>
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

<p>Tests whether the target is wasm (32- and 64-bit).</p>

<p>Definition at line 1064 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ac0478f40eaacc5f340e93827756e7a33">wasm32</a> and <a href="#a547abd13f7a3c063aa72c8192a868154ad6b7ed7027706d2960e771c6374025b1">wasm64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa441f906c99d29f50a64369799d8f737">llvm::DwarfDebug::emitDebugLocValue</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ac5b407054e7727d04053af9c3f1a5568">llvm::OpenMPIRBuilder::getOpenMPDefaultSimdAlign</a> and <a href="#a553e5eede76e94cc97f728aee36cec71">hasDefaultDataSections</a>.</p>

</div>
</div>

### isWatchABI {#a14aca434442ff741fa55e97ddccd15ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isWatchABI ()</td>
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



<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a9ffca842bbaefcf99484f59a83b618d4a310c3af47d446eeaea76dd7ce69241f5">ARMSubArch_v7k</a> and <a href="#a2f6aa922f9f6991e7d8aecb147e08fd4">getSubArch</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armmcasminfodarwin/#a9431bd9edb8400058b9caccf2c38f21e">llvm::ARMMCAsmInfoDarwin::ARMMCAsmInfoDarwin</a>.</p>

</div>
</div>

### isWatchOS {#ac2eddca981f187178a53969d88465b4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isWatchOS ()</td>
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

<p>Is this an Apple watchOS triple.</p>

<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cda87a3c8454473c64f6d605ebd757759ad">WatchOS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a> and <a href="#ab6fdf9b428bc3d57837022121c155cbf">isOSDarwin</a>.</p>

</div>
</div>

### isWindowsArm64EC {#ac0544a852d0033d3980285dbd1133ac6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isWindowsArm64EC ()</td>
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



<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">aarch64</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4ac4c8930e0836b52270b435d71f98bdb0">AArch64SubArch_arm64ec</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a> and <a href="#a2f6aa922f9f6991e7d8aecb147e08fd4">getSubArch</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8476d36f91161750b845b56f25cb7c47">llvm::AArch64MCInstLower::GetGlobalValueSymbol</a>.</p>

</div>
</div>

### isWindowsCoreCLREnvironment {#a4aff54e7e4562b21d5762a6ca406f9f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isWindowsCoreCLREnvironment ()</td>
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



<p>Definition at line 679 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a1778f5c464f88710033f7e11e84a9324afcb832e2cb16856e53500d3c1e52a890">CoreCLR</a>, <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a> and <a href="#a7736bfc4c1afef875ecf02f2a7701fe3">isOSWindows</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#aeafb06413605da840d52ad76655540e8">createX86MCAsmInfo</a>.</p>

</div>
</div>

### isWindowsCygwinEnvironment {#aa0fd88c696cfbb5c2648fe705dcdef5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isWindowsCygwinEnvironment ()</td>
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



<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a1778f5c464f88710033f7e11e84a9324a0521408131ca98c3ee4f486df216ea39">Cygnus</a>, <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a> and <a href="#a7736bfc4c1afef875ecf02f2a7701fe3">isOSWindows</a>.</p>


<p>Referenced by <a href="#ade012f998cea3bc03f6da0b08d422e6c">hasDefaultEmulatedTLS</a> and <a href="#a145fccafbd4d3bb9ff459092d5a5616b">isOSCygMing</a>.</p>

</div>
</div>

### isWindowsGNUEnvironment {#a398f3f1f57fae295ca4ae75a3b56fa59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isWindowsGNUEnvironment ()</td>
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



<p>Definition at line 691 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ae6c91532448c0be7978cf1bfcdaa11bb">GNU</a> and <a href="#a7736bfc4c1afef875ecf02f2a7701fe3">isOSWindows</a>.</p>


<p>Referenced by <a href="#ae86f9f850769a4896b883b0da1322a51">isCompatibleWith</a>, <a href="#a145fccafbd4d3bb9ff459092d5a5616b">isOSCygMing</a> and <a href="#a438b0136b755625f50ea227cc19e5ad9">isOSMSVCRT</a>.</p>

</div>
</div>

### isWindowsItaniumEnvironment {#afdd0d3d27ef11fd6ad21da63c3979d77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isWindowsItaniumEnvironment ()</td>
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



<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a>, <a href="#a7736bfc4c1afef875ecf02f2a7701fe3">isOSWindows</a> and <a href="#a1778f5c464f88710033f7e11e84a9324aa97aa42b85b1502e458177c354ab6788">Itanium</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#aeafb06413605da840d52ad76655540e8">createX86MCAsmInfo</a> and <a href="#a438b0136b755625f50ea227cc19e5ad9">isOSMSVCRT</a>.</p>

</div>
</div>

### isWindowsMSVCEnvironment {#aed5b9fcccfe88a419343c80064d44d74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isWindowsMSVCEnvironment ()</td>
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

<p>Checks if the environment could be MSVC.</p>

<p>Definition at line 668 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a>, <a href="#af6d6a4d950ccaa3be4ca4ff2f2169090">isKnownWindowsMSVCEnvironment</a>, <a href="#a7736bfc4c1afef875ecf02f2a7701fe3">isOSWindows</a> and <a href="#a1778f5c464f88710033f7e11e84a9324a6c32bcd90dff79307baf3147697ae1d3">UnknownEnvironment</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ae215c9475e5b6a8ae5efa8ff60202dfe">createAArch64MCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#af517e546ece4970a718601f99698bb82">createARMMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#aeafb06413605da840d52ad76655540e8">createX86MCAsmInfo</a> and <a href="#a438b0136b755625f50ea227cc19e5ad9">isOSMSVCRT</a>.</p>

</div>
</div>

### isX32 {#a292887fa6b4aa078f520d5884dda7ad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isX32 ()</td>
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

<p>Tests whether the target is X32.</p>

<p>Definition at line 1086 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ab0c4c38b98e3b1482fc1c5afc8649e28">GNUX32</a> and <a href="#a1778f5c464f88710033f7e11e84a9324ae2e0845b94acce4ef8966096195201dd">MuslX32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a306674e8951ad0f9c77cda2f70219ab9">llvm::createX86_64AsmBackend</a>.</p>

</div>
</div>

### isX86 {#a31d94b95418472bb1179f7c130ad3667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isX86 ()</td>
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

<p>Tests whether the target is x86 (32- or 64-bit).</p>

<p>Definition at line 1054 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">x86</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">x86_64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ac5b407054e7727d04053af9c3f1a5568">llvm::OpenMPIRBuilder::getOpenMPDefaultSimdAlign</a>.</p>

</div>
</div>

### isXROS {#aaba295444f638da56e58010cf7fb091d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::isXROS ()</td>
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

<p>Is this an Apple XROS triple.</p>

<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cdabb5225659a201976ce2594df579e3623">XROS</a>.</p>


<p>Referenced by <a href="#ab6fdf9b428bc3d57837022121c155cbf">isOSDarwin</a>.</p>

</div>
</div>

### supportsCOMDAT {#a49a399e1ef632107f1a062a3d22f2118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Triple::supportsCOMDAT ()</td>
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

<p>Tests whether the target supports comdat.</p>

<p>Definition at line 1113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>.</p>


<p>References <a href="#a7df3ae0918bd700a9c8507e3b158e06f">isOSBinFormatDXContainer</a>, <a href="#a444e46ff0a17a6c9480eb151bd42c9bc">isOSBinFormatMachO</a> and <a href="#a804d3966ad6c4daafeb8a7ae31b8ae2d">isOSBinFormatXCOFF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a580ea5c66929553cd9bdc5741fbe2b1a">llvm::needsComdatForCounter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Mutators

### setArch {#af70f4019638c4a7cccaaad403c25c048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Triple::setArch (<a href="#a547abd13f7a3c063aa72c8192a868154">ArchType</a> Kind, <a href="#a9ffca842bbaefcf99484f59a83b618d4">SubArchType</a> SubArch=<a href="#a9ffca842bbaefcf99484f59a83b618d4a023f1e73b058ea58dba15516382eed52">NoSubArch</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the architecture (first) component of the triple to a known type.</p>

<p>Declaration at line 1143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1581 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#ad2d9e5a5c22d594a05d4feae337de252">getArchName</a> and <a href="#a096c1f8d7977e175075e210101627e0b">setArchName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a9a9a7989eeb174879ae8581e33e61824">llvm::TargetRegistry::lookupTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a6f6cda42b5be79b59179a5ca1a3e7bfa">llvm::object::ObjectFile::makeTriple</a> and <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a7ef5bb146eb2c0e3a609a6a169ac4f44">llvm::EngineBuilder::selectTarget</a>.</p>

</div>
</div>

### setArchName {#a096c1f8d7977e175075e210101627e0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Triple::setArchName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the architecture (first) component of the triple by name.</p>

<p>Declaration at line 1161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1609 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a9e404426d1eac2b4c19c8986d9d46cb3">getOSAndEnvironmentName</a>, <a href="#a062f684a024e13d7280e178c95668678">getVendorName</a>, <a href="#a58ffeec08324cdbd301158e5ef874cc3">setTriple</a> and <a href="#a15410866a30d89459a6f99034202e475">Triple</a>.</p>


<p>Referenced by <a href="#af70f4019638c4a7cccaaad403c25c048">setArch</a> and <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#aedba1742067f82fe193a19daf690cd06">llvm::object::ELFObjectFileBase::setARMSubArch</a>.</p>

</div>
</div>

### setEnvironment {#a472091dc314efebea60a6c5cff416cc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Triple::setEnvironment (<a href="#a1778f5c464f88710033f7e11e84a9324">EnvironmentType</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the environment (fourth) component of the triple to a known type.</p>

<p>Declaration at line 1152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1593 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a593094f6c13df699bd2cde1a1f40fec4">getDefaultFormat</a>, <a href="#abb703efa7aa5bddf5875fe8f2517e787">getEnvironmentTypeName</a>, <a href="#ada671e44e91b68a18f8a61f12dd1f475">getObjectFormatTypeName</a>, <a href="#aac154976a48deecf23babdeb1be05d9f">setEnvironmentName</a> and <a href="#a6ad662bdf0613457ae9b81b47f5555b7">str</a>.</p>

</div>
</div>

### setEnvironmentName {#aac154976a48deecf23babdeb1be05d9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Triple::setEnvironmentName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the optional environment (fourth) component of the triple by name.</p>

<p>Declaration at line 1170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1632 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#ad2d9e5a5c22d594a05d4feae337de252">getArchName</a>, <a href="#a483bbccede7948c656b0bd339f39218f">getOSName</a>, <a href="#a062f684a024e13d7280e178c95668678">getVendorName</a> and <a href="#a58ffeec08324cdbd301158e5ef874cc3">setTriple</a>.</p>


<p>Referenced by <a href="#a472091dc314efebea60a6c5cff416cc9">setEnvironment</a> and <a href="#a0e2cea374a7428eb1b5ec87ef774e552">setObjectFormat</a>.</p>

</div>
</div>

### setObjectFormat {#a0e2cea374a7428eb1b5ec87ef774e552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Triple::setObjectFormat (<a href="#a83e907e55fa50e093caa96a0aff96201">ObjectFormatType</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the object file format.</p>

<p>Declaration at line 1155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1601 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#abb703efa7aa5bddf5875fe8f2517e787">getEnvironmentTypeName</a>, <a href="#ada671e44e91b68a18f8a61f12dd1f475">getObjectFormatTypeName</a>, <a href="#aac154976a48deecf23babdeb1be05d9f">setEnvironmentName</a>, <a href="#a6ad662bdf0613457ae9b81b47f5555b7">str</a> and <a href="#a1778f5c464f88710033f7e11e84a9324a6c32bcd90dff79307baf3147697ae1d3">UnknownEnvironment</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a6f6cda42b5be79b59179a5ca1a3e7bfa">llvm::object::ObjectFile::makeTriple</a>.</p>

</div>
</div>

### setOS {#aadd45e5c167eb85f1741ee869ea790e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Triple::setOS (<a href="#a3cfefc755ab656000934f91193afb1cd">OSType</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the operating system (third) component of the triple to a known type.</p>

<p>Declaration at line 1149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1589 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a8192d4072e4aaba803248250d1faf61c">getOSTypeName</a> and <a href="#ab3500e69a89f930107cd6f067371da4a">setOSName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a6f6cda42b5be79b59179a5ca1a3e7bfa">llvm::object::ObjectFile::makeTriple</a>.</p>

</div>
</div>

### setOSAndEnvironmentName {#a3eaa25de6a989d7332fa6044b3707226}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Triple::setOSAndEnvironmentName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the operating system and optional environment components with a single string.</p>

<p>Declaration at line 1174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1637 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#ad2d9e5a5c22d594a05d4feae337de252">getArchName</a>, <a href="#a062f684a024e13d7280e178c95668678">getVendorName</a> and <a href="#a58ffeec08324cdbd301158e5ef874cc3">setTriple</a>.</p>

</div>
</div>

### setOSName {#ab3500e69a89f930107cd6f067371da4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Triple::setOSName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the operating system (third) component of the triple by name.</p>

<p>Declaration at line 1167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1624 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#ad2d9e5a5c22d594a05d4feae337de252">getArchName</a>, <a href="#a685d4808dcb1ae5133120d64593d515b">getEnvironmentName</a>, <a href="#a062f684a024e13d7280e178c95668678">getVendorName</a>, <a href="#aee1760b5f339b38a6f711a2794cf0350">hasEnvironment</a> and <a href="#a58ffeec08324cdbd301158e5ef874cc3">setTriple</a>.</p>


<p>Referenced by <a href="#aadd45e5c167eb85f1741ee869ea790e8">setOS</a>.</p>

</div>
</div>

### setTriple {#a58ffeec08324cdbd301158e5ef874cc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Triple::setTriple (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set all components to the new triple <span class="doxyComputerOutput">Str</span>.</p>

<p>Declaration at line 1158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1577 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>Reference <a href="#a15410866a30d89459a6f99034202e475">Triple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a6f6cda42b5be79b59179a5ca1a3e7bfa">llvm::object::ObjectFile::makeTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a7ef5bb146eb2c0e3a609a6a169ac4f44">llvm::EngineBuilder::selectTarget</a>, <a href="#a096c1f8d7977e175075e210101627e0b">setArchName</a>, <a href="#aac154976a48deecf23babdeb1be05d9f">setEnvironmentName</a>, <a href="#a3eaa25de6a989d7332fa6044b3707226">setOSAndEnvironmentName</a>, <a href="#ab3500e69a89f930107cd6f067371da4a">setOSName</a>, <a href="#a3a48b7e3794824f1fa399052765074ff">setVendorName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6d9c43797976f73bdbe0c75995f84865">llvm::SPIRVTranslate</a>.</p>

</div>
</div>

### setVendor {#af96094469e937492a76dd8e01e81e7cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Triple::setVendor (<a href="#a96fe35195867c94aef1adf2ad0e20eec">VendorType</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the vendor (second) component of the triple to a known type.</p>

<p>Declaration at line 1146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1585 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a298fc373d25fb899e8963abf7f88e2e0">getVendorTypeName</a> and <a href="#a3a48b7e3794824f1fa399052765074ff">setVendorName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a6f6cda42b5be79b59179a5ca1a3e7bfa">llvm::object::ObjectFile::makeTriple</a>.</p>

</div>
</div>

### setVendorName {#a3a48b7e3794824f1fa399052765074ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Triple::setVendorName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the vendor (second) component of the triple by name.</p>

<p>Declaration at line 1164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1620 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#ad2d9e5a5c22d594a05d4feae337de252">getArchName</a>, <a href="#a9e404426d1eac2b4c19c8986d9d46cb3">getOSAndEnvironmentName</a> and <a href="#a58ffeec08324cdbd301158e5ef874cc3">setTriple</a>.</p>


<p>Referenced by <a href="#af96094469e937492a76dd8e01e81e7cc">setVendor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Helpers to build variants of a particular triple.

### get32BitArchVariant {#a13e7af62cc56f460209e36190829d78c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple Triple::get32BitArchVariant ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Form a triple with a 32-bit variant of the current architecture.</p>


<p>This can be used to move across "families" of architectures where useful.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A new triple with a 32-bit architecture or an unknown architecture if no such variant can be found.</p></dd>
</dl>


<p>Declaration at line 1186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1746 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">aarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">aarch64_32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">aarch64_be</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">amdgcn</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5ea1b051c09d0127f2d90e0ad6b487df">amdil</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ade794c636782fc46854cb047c40c164b">amdil64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aed5f38c6bd089f09c02aae8072ceb514">arc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">arm</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af65ab1964be676bea302940a45765021">armeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9b780628857be980e628bf44ae7dce56">avr</a>, <a href="#a547abd13f7a3c063aa72c8192a868154abccdd747b05d7cfff6ae937ffdf5ba03">bpfeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a83d003d0efa0cd997646dc0343d7093f">bpfel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a21a4eb647191d4bd084ffdd749dd9100">csky</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ca957896440ddfeeedda9c05723c150">dxil</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a2f6aa922f9f6991e7d8aecb147e08fd4">getSubArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5770b66a2436004885ac116a8ac357d5">hexagon</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aca408a723390395eeaa343d8f1e307c4">hsail</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a74533b62667da81390b35d2a47709458">hsail64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5c48161b8fa1243dfab0169510c72bb1">kalimba</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8ccdc49befcb57d683a4ed2025a7f60d">lanai</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0c64155961d19dceb44b43f5a9992d1a">loongarch32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">loongarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae3dbf1f961e0618ea793bc9c099b932a">m68k</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">mips</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">mips64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">mips64el</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">mipsel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a752f0f4d07cf7dcdbe539a95dfe4cbff">msp430</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae06ff88d5da98b63a6b4397fcb7a6050">nvptx</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a92ac53f0fca7e6c3f4e56a2d4903b9ae">nvptx64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">ppc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">ppc64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">ppc64le</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">ppcle</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a060ea888d89f5d59a5743118e429296f">r600</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a863d4793e08f6a5a3ca20149b3e7a85d">renderscript32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a1c43e5f860c9e21dab6fcfc65f93945d">renderscript64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae84559483d0c0f2bddc802ce6f76dd8b">riscv32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08">riscv64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a396b3f1df93fc8cb904b66759a0d1a96">shave</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ebafd1adc05a751215ae959f2891752">sparc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a069fe14c1b6db6a31124817f2e57c954">sparcel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a34e8fe940082d534b3957f06616c8227">sparcv9</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a475e7f13c36b181edba29cfcca212def">spir</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5973589725994222a16112b960c74323">spir64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aeee38b63a639e89548c0efc74cab3b65">spirv</a>, <a href="#a547abd13f7a3c063aa72c8192a868154afc429c7efea3699ead2afe26b7db09df">spirv32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae0a08d9852914cec82b405e32e87fbdc">spirv64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">systemz</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ad7837c42372169017a6e5ff3eaa42d1d">tce</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8f07c386f3b82ef15a54318946248f96">tcele</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">thumb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a038a23cbd1756bf797c083c48229dcfd">thumbeb</a>, <a href="#a15410866a30d89459a6f99034202e475">Triple</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">UnknownArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a419abb6aa1b60e8d534b06311c1e553c">ve</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ac0478f40eaacc5f340e93827756e7a33">wasm32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ad6b7ed7027706d2960e771c6374025b1">wasm64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">x86</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">x86_64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a1e3f00d3a8c8c59f0f95fd80f1d3ba53">xcore</a> and <a href="#a547abd13f7a3c063aa72c8192a868154ab9cc677b26266a0658a4f6feb4ee0bdc">xtensa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sys/#aab375071f641a086c0d7067635ccd3dc">llvm::sys::getProcessTriple</a>.</p>

</div>
</div>

### get64BitArchVariant {#a424c4dc4d08741fa4615cc0c4ec956bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple Triple::get64BitArchVariant ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Form a triple with a 64-bit variant of the current architecture.</p>


<p>This can be used to move across "families" of architectures where useful.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A new triple with a 64-bit architecture or an unknown architecture if no such variant can be found.</p></dd>
</dl>


<p>Declaration at line 1194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1825 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">aarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">aarch64_32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">aarch64_be</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">amdgcn</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5ea1b051c09d0127f2d90e0ad6b487df">amdil</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ade794c636782fc46854cb047c40c164b">amdil64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aed5f38c6bd089f09c02aae8072ceb514">arc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">arm</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af65ab1964be676bea302940a45765021">armeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9b780628857be980e628bf44ae7dce56">avr</a>, <a href="#a547abd13f7a3c063aa72c8192a868154abccdd747b05d7cfff6ae937ffdf5ba03">bpfeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a83d003d0efa0cd997646dc0343d7093f">bpfel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a21a4eb647191d4bd084ffdd749dd9100">csky</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ca957896440ddfeeedda9c05723c150">dxil</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a2f6aa922f9f6991e7d8aecb147e08fd4">getSubArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5770b66a2436004885ac116a8ac357d5">hexagon</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aca408a723390395eeaa343d8f1e307c4">hsail</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a74533b62667da81390b35d2a47709458">hsail64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5c48161b8fa1243dfab0169510c72bb1">kalimba</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8ccdc49befcb57d683a4ed2025a7f60d">lanai</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0c64155961d19dceb44b43f5a9992d1a">loongarch32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">loongarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae3dbf1f961e0618ea793bc9c099b932a">m68k</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">mips</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">mips64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">mips64el</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">mipsel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a752f0f4d07cf7dcdbe539a95dfe4cbff">msp430</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae06ff88d5da98b63a6b4397fcb7a6050">nvptx</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a92ac53f0fca7e6c3f4e56a2d4903b9ae">nvptx64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">ppc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">ppc64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">ppc64le</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">ppcle</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a060ea888d89f5d59a5743118e429296f">r600</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a863d4793e08f6a5a3ca20149b3e7a85d">renderscript32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a1c43e5f860c9e21dab6fcfc65f93945d">renderscript64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae84559483d0c0f2bddc802ce6f76dd8b">riscv32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08">riscv64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a396b3f1df93fc8cb904b66759a0d1a96">shave</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ebafd1adc05a751215ae959f2891752">sparc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a069fe14c1b6db6a31124817f2e57c954">sparcel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a34e8fe940082d534b3957f06616c8227">sparcv9</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a475e7f13c36b181edba29cfcca212def">spir</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5973589725994222a16112b960c74323">spir64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aeee38b63a639e89548c0efc74cab3b65">spirv</a>, <a href="#a547abd13f7a3c063aa72c8192a868154afc429c7efea3699ead2afe26b7db09df">spirv32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae0a08d9852914cec82b405e32e87fbdc">spirv64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">systemz</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ad7837c42372169017a6e5ff3eaa42d1d">tce</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8f07c386f3b82ef15a54318946248f96">tcele</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">thumb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a038a23cbd1756bf797c083c48229dcfd">thumbeb</a>, <a href="#a15410866a30d89459a6f99034202e475">Triple</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">UnknownArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a419abb6aa1b60e8d534b06311c1e553c">ve</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ac0478f40eaacc5f340e93827756e7a33">wasm32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ad6b7ed7027706d2960e771c6374025b1">wasm64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">x86</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">x86_64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a1e3f00d3a8c8c59f0f95fd80f1d3ba53">xcore</a> and <a href="#a547abd13f7a3c063aa72c8192a868154ab9cc677b26266a0658a4f6feb4ee0bdc">xtensa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sys/#aab375071f641a086c0d7067635ccd3dc">llvm::sys::getProcessTriple</a>.</p>

</div>
</div>

### getBigEndianArchVariant {#adb7bb8c037a9662d31b148af4efa2a5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple Triple::getBigEndianArchVariant ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Form a triple with a big endian variant of the current architecture.</p>


<p>This can be used to move across "families" of architectures where useful.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A new triple with a big endian architecture or an unknown architecture if no such variant can be found.</p></dd>
</dl>


<p>Declaration at line 1202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1904 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">aarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">aarch64_be</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">amdgcn</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5ea1b051c09d0127f2d90e0ad6b487df">amdil</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ade794c636782fc46854cb047c40c164b">amdil64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">arm</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9b780628857be980e628bf44ae7dce56">avr</a>, <a href="#a547abd13f7a3c063aa72c8192a868154abccdd747b05d7cfff6ae937ffdf5ba03">bpfeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a83d003d0efa0cd997646dc0343d7093f">bpfel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a21a4eb647191d4bd084ffdd749dd9100">csky</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ca957896440ddfeeedda9c05723c150">dxil</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a2f6aa922f9f6991e7d8aecb147e08fd4">getSubArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5770b66a2436004885ac116a8ac357d5">hexagon</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aca408a723390395eeaa343d8f1e307c4">hsail</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a74533b62667da81390b35d2a47709458">hsail64</a>, <a href="#a45678567c4d2b54e70800daa41897207">isLittleEndian</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5c48161b8fa1243dfab0169510c72bb1">kalimba</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0c64155961d19dceb44b43f5a9992d1a">loongarch32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">loongarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">mips</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">mips64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">mips64el</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">mipsel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a752f0f4d07cf7dcdbe539a95dfe4cbff">msp430</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae06ff88d5da98b63a6b4397fcb7a6050">nvptx</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a92ac53f0fca7e6c3f4e56a2d4903b9ae">nvptx64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">ppc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">ppc64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">ppc64le</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">ppcle</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a060ea888d89f5d59a5743118e429296f">r600</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a863d4793e08f6a5a3ca20149b3e7a85d">renderscript32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a1c43e5f860c9e21dab6fcfc65f93945d">renderscript64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae84559483d0c0f2bddc802ce6f76dd8b">riscv32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08">riscv64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a396b3f1df93fc8cb904b66759a0d1a96">shave</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ebafd1adc05a751215ae959f2891752">sparc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a069fe14c1b6db6a31124817f2e57c954">sparcel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a475e7f13c36b181edba29cfcca212def">spir</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5973589725994222a16112b960c74323">spir64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aeee38b63a639e89548c0efc74cab3b65">spirv</a>, <a href="#a547abd13f7a3c063aa72c8192a868154afc429c7efea3699ead2afe26b7db09df">spirv32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae0a08d9852914cec82b405e32e87fbdc">spirv64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ad7837c42372169017a6e5ff3eaa42d1d">tce</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8f07c386f3b82ef15a54318946248f96">tcele</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">thumb</a>, <a href="#a15410866a30d89459a6f99034202e475">Triple</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">UnknownArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a419abb6aa1b60e8d534b06311c1e553c">ve</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ac0478f40eaacc5f340e93827756e7a33">wasm32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ad6b7ed7027706d2960e771c6374025b1">wasm64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">x86</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">x86_64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a1e3f00d3a8c8c59f0f95fd80f1d3ba53">xcore</a> and <a href="#a547abd13f7a3c063aa72c8192a868154ab9cc677b26266a0658a4f6feb4ee0bdc">xtensa</a>.</p>

</div>
</div>

### getLittleEndianArchVariant {#a269e50214be37e2963f53f94518a1894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple Triple::getLittleEndianArchVariant ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Form a triple with a little endian variant of the current architecture.</p>


<p>This can be used to move across "families" of architectures where useful.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A new triple with a little endian architecture or an unknown architecture if no such variant can be found.</p></dd>
</dl>


<p>Declaration at line 1210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 1970 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">aarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">aarch64_be</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af65ab1964be676bea302940a45765021">armeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154abccdd747b05d7cfff6ae937ffdf5ba03">bpfeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a83d003d0efa0cd997646dc0343d7093f">bpfel</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a2f6aa922f9f6991e7d8aecb147e08fd4">getSubArch</a>, <a href="#a45678567c4d2b54e70800daa41897207">isLittleEndian</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8ccdc49befcb57d683a4ed2025a7f60d">lanai</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae3dbf1f961e0618ea793bc9c099b932a">m68k</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">mips</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">mips64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">mips64el</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">mipsel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">ppc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">ppc64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">ppc64le</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">ppcle</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ebafd1adc05a751215ae959f2891752">sparc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a069fe14c1b6db6a31124817f2e57c954">sparcel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a34e8fe940082d534b3957f06616c8227">sparcv9</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">systemz</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ad7837c42372169017a6e5ff3eaa42d1d">tce</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8f07c386f3b82ef15a54318946248f96">tcele</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a038a23cbd1756bf797c083c48229dcfd">thumbeb</a>, <a href="#a15410866a30d89459a6f99034202e475">Triple</a> and <a href="#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">UnknownArch</a>.</p>

</div>
</div>

### getMinimumSupportedOSVersion {#a9b7155e7913c06217d85f6a7a3250315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple Triple::getMinimumSupportedOSVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Some platforms have different minimum supported OS versions that varies by the architecture specified in the triple.</p>


<p>This function returns the minimum supported OS version for this triple if one an exists, or an invalid version tuple if this triple doesn't have one.</p>


<p>Declaration at line 1227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 2120 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">aarch64</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eeca674d908c8b0ebe1880f8c8d651eda9e2">Apple</a>, <a href="#a3cfefc755ab656000934f91193afb1cda600aa0b72f321a0cdf0e4b3f38b9b6c8">DriverKit</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>, <a href="#ab4d9af9c278219b313508fce336b7d83">getVendor</a>, <a href="#a3cfefc755ab656000934f91193afb1cdafad6e6763679be1478d9283a7344d243">IOS</a>, <a href="#a32dff8f6f7ea462f82443a33fdf1e4ac">isArm64e</a>, <a href="#ad7328346f2f8d6b9d897608882bc7758">isMacCatalystEnvironment</a>, <a href="#a6a66d02819186762f85145d632f9f81f">isSimulatorEnvironment</a>, <a href="#a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075">MacOSX</a>, <a href="#a3cfefc755ab656000934f91193afb1cda2838cf6df0f09591c50d752d46c4350d">TvOS</a> and <a href="#a3cfefc755ab656000934f91193afb1cda87a3c8454473c64f6d605ebd757759ad">WatchOS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a44bd2d03a8b75fb4924e7f83430c0c71">llvm::MachO::mapToSupportedOSVersion</a>.</p>

</div>
</div>

### isCompatibleWith {#ae86f9f850769a4896b883b0da1322a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Triple::isCompatibleWith (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether target triples are compatible.</p>

<p>Declaration at line 1218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 2059 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a96fe35195867c94aef1adf2ad0e20eeca674d908c8b0ebe1880f8c8d651eda9e2">Apple</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">arm</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af65ab1964be676bea302940a45765021">armeb</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a6beb910ab0112de8679b6d2703351384">getEnvironment</a>, <a href="#a2e265a0d332c3e2db0acf0c7afd4175d">getObjectFormat</a>, <a href="#a5a777de4cd152c5b22b9d28439326d50">getOS</a>, <a href="#a2f6aa922f9f6991e7d8aecb147e08fd4">getSubArch</a>, <a href="#ab4d9af9c278219b313508fce336b7d83">getVendor</a>, <a href="#a398f3f1f57fae295ca4ae75a3b56fa59">isWindowsGNUEnvironment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">thumb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a038a23cbd1756bf797c083c48229dcfd">thumbeb</a> and <a href="#a15410866a30d89459a6f99034202e475">Triple</a>.</p>

</div>
</div>

### isLittleEndian {#a45678567c4d2b54e70800daa41897207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Triple::isLittleEndian ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tests whether the target triple is little endian.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the triple is little endian, false otherwise.</p></dd>
</dl>


<p>Declaration at line 1215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 2007 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">aarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">aarch64_32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">amdgcn</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5ea1b051c09d0127f2d90e0ad6b487df">amdil</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ade794c636782fc46854cb047c40c164b">amdil64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">arm</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9b780628857be980e628bf44ae7dce56">avr</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a83d003d0efa0cd997646dc0343d7093f">bpfel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a21a4eb647191d4bd084ffdd749dd9100">csky</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ca957896440ddfeeedda9c05723c150">dxil</a>, <a href="#a5fc23559f17bbe5ff83ec0fed0a5fdcf">getArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5770b66a2436004885ac116a8ac357d5">hexagon</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aca408a723390395eeaa343d8f1e307c4">hsail</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a74533b62667da81390b35d2a47709458">hsail64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5c48161b8fa1243dfab0169510c72bb1">kalimba</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0c64155961d19dceb44b43f5a9992d1a">loongarch32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">loongarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">mips64el</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">mipsel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a752f0f4d07cf7dcdbe539a95dfe4cbff">msp430</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae06ff88d5da98b63a6b4397fcb7a6050">nvptx</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a92ac53f0fca7e6c3f4e56a2d4903b9ae">nvptx64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">ppc64le</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">ppcle</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a060ea888d89f5d59a5743118e429296f">r600</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a863d4793e08f6a5a3ca20149b3e7a85d">renderscript32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a1c43e5f860c9e21dab6fcfc65f93945d">renderscript64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae84559483d0c0f2bddc802ce6f76dd8b">riscv32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08">riscv64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a396b3f1df93fc8cb904b66759a0d1a96">shave</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a069fe14c1b6db6a31124817f2e57c954">sparcel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a475e7f13c36b181edba29cfcca212def">spir</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5973589725994222a16112b960c74323">spir64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aeee38b63a639e89548c0efc74cab3b65">spirv</a>, <a href="#a547abd13f7a3c063aa72c8192a868154afc429c7efea3699ead2afe26b7db09df">spirv32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae0a08d9852914cec82b405e32e87fbdc">spirv64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8f07c386f3b82ef15a54318946248f96">tcele</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">thumb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a419abb6aa1b60e8d534b06311c1e553c">ve</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ac0478f40eaacc5f340e93827756e7a33">wasm32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ad6b7ed7027706d2960e771c6374025b1">wasm64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">x86</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">x86_64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a1e3f00d3a8c8c59f0f95fd80f1d3ba53">xcore</a> and <a href="#a547abd13f7a3c063aa72c8192a868154ab9cc677b26266a0658a4f6feb4ee0bdc">xtensa</a>.</p>


<p>Referenced by <a href="#adb7bb8c037a9662d31b148af4efa2a5a">getBigEndianArchVariant</a>, <a href="#a269e50214be37e2963f53f94518a1894">getLittleEndianArchVariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp/#a675f0690b04eaa2c63f91d8e05c75106">getUUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a8d6169e2e4a0e60c74e95dab53907e2f">lowerMSASplatZExt</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsasmparser/#a96cded7294d54537fbb8eb5a6148448a">anonymous{MipsAsmParser.cpp}::MipsAsmParser::MipsAsmParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfmcasminfo/#a8708ca800840e855dc74da7c335cae33">llvm::MipsELFMCAsmInfo::MipsELFMCAsmInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#aac98d18ebaf02ce89cd8783f59aad2d0">llvm::ifs::parseTriple</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a08f16f302c998119c978d7ce93b4c569">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::tagAlloca</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a601c710d4a4ed9a073bd55ea552d5645">truncateVecElts</a>.</p>

</div>
</div>

### merge {#a8605d2bf7adf880652f2a4fe11ca050d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string Triple::merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge target triples.</p>

<p>Declaration at line 1221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 2094 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a96fe35195867c94aef1adf2ad0e20eeca674d908c8b0ebe1880f8c8d651eda9e2">Apple</a>, <a href="#ab4d9af9c278219b313508fce336b7d83">getVendor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a6ad662bdf0613457ae9b81b47f5555b7">str</a> and <a href="#a15410866a30d89459a6f99034202e475">Triple</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Static helpers for IDs.

### getArchName {#a19adff7744a0fe75c2c083e6d9b710e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Triple::getArchName (<a href="#a547abd13f7a3c063aa72c8192a868154">ArchType</a> Kind, <a href="#a9ffca842bbaefcf99484f59a83b618d4">SubArchType</a> SubArch=<a href="#a9ffca842bbaefcf99484f59a83b618d4a023f1e73b058ea58dba15516382eed52">NoSubArch</a>)</td>
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

<p>Get the architecture name based on <span class="doxyComputerOutput">Kind</span> and <span class="doxyComputerOutput">SubArch</span>.</p>

<p>Declaration at line 1237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">aarch64</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a68fc64acd599f1efceab58c5b1c948c1">AArch64SubArch_arm64e</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4ac4c8930e0836b52270b435d71f98bdb0">AArch64SubArch_arm64ec</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ca957896440ddfeeedda9c05723c150">dxil</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a954e732fd72626ce869a6b38c050495d">DXILSubArch_v1_0</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a202ec88c46325bdf865ca5a1f5819cb0">DXILSubArch_v1_1</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a0e4443406aadf87efa04d1ebeb8bec3a">DXILSubArch_v1_2</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a52965fe3bf486e8497500b37cab6273a">DXILSubArch_v1_3</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4af083ca354398e0eba40123becd94226f">DXILSubArch_v1_4</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a9b088b1eec5001ea047b8bcf2d1e0921">DXILSubArch_v1_5</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4ad09a2cbaf1d4a9851a4b332da0616e85">DXILSubArch_v1_6</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a959c52d31d7bbee0a429ea61faf01bed">DXILSubArch_v1_7</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4ad54b83d8c0ad287435344c7693fbe686">DXILSubArch_v1_8</a>, <a href="#a7c78e5759f86ae499cd06dfc747464a9">getArchTypeName</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">mips</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">mips64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">mips64el</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">mipsel</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a06ae0d5f23c7c3ab80c4a241a7489385">MipsSubArch_r6</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a023f1e73b058ea58dba15516382eed52">NoSubArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aeee38b63a639e89548c0efc74cab3b65">spirv</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a28f0d364a91de157afe87b7a37f4482f">SPIRVSubArch_v10</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4af683dac34822e36580d0a321f68af416">SPIRVSubArch_v11</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4abbfc31485ff4538616ec4781b43e84ed">SPIRVSubArch_v12</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a2aa494dc61832706e97f2e3754d08fed">SPIRVSubArch_v13</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4abe4d0a4aeeee8ba9fad55d5be3375c0a">SPIRVSubArch_v14</a>, <a href="#a9ffca842bbaefcf99484f59a83b618d4a56d1bb97744ae0c6b4a62d7057b8b3c9">SPIRVSubArch_v15</a> and <a href="#a9ffca842bbaefcf99484f59a83b618d4a4c3a9a3e3252bd79135d70a26bffb83b">SPIRVSubArch_v16</a>.</p>

</div>
</div>

### getArchTypeName {#a7c78e5759f86ae499cd06dfc747464a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Triple::getArchTypeName (<a href="#a547abd13f7a3c063aa72c8192a868154">ArchType</a> Kind)</td>
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

<p>Get the canonical name for the <span class="doxyComputerOutput">Kind</span> architecture.</p>

<p>Declaration at line 1234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">aarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">aarch64_32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">aarch64_be</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">amdgcn</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5ea1b051c09d0127f2d90e0ad6b487df">amdil</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ade794c636782fc46854cb047c40c164b">amdil64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aed5f38c6bd089f09c02aae8072ceb514">arc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">arm</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af65ab1964be676bea302940a45765021">armeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9b780628857be980e628bf44ae7dce56">avr</a>, <a href="#a547abd13f7a3c063aa72c8192a868154abccdd747b05d7cfff6ae937ffdf5ba03">bpfeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a83d003d0efa0cd997646dc0343d7093f">bpfel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a21a4eb647191d4bd084ffdd749dd9100">csky</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ca957896440ddfeeedda9c05723c150">dxil</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5770b66a2436004885ac116a8ac357d5">hexagon</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aca408a723390395eeaa343d8f1e307c4">hsail</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a74533b62667da81390b35d2a47709458">hsail64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5c48161b8fa1243dfab0169510c72bb1">kalimba</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8ccdc49befcb57d683a4ed2025a7f60d">lanai</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0c64155961d19dceb44b43f5a9992d1a">loongarch32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">loongarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae3dbf1f961e0618ea793bc9c099b932a">m68k</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">mips</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">mips64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">mips64el</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">mipsel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a752f0f4d07cf7dcdbe539a95dfe4cbff">msp430</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae06ff88d5da98b63a6b4397fcb7a6050">nvptx</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a92ac53f0fca7e6c3f4e56a2d4903b9ae">nvptx64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">ppc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">ppc64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">ppc64le</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">ppcle</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a060ea888d89f5d59a5743118e429296f">r600</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a863d4793e08f6a5a3ca20149b3e7a85d">renderscript32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a1c43e5f860c9e21dab6fcfc65f93945d">renderscript64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae84559483d0c0f2bddc802ce6f76dd8b">riscv32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08">riscv64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a396b3f1df93fc8cb904b66759a0d1a96">shave</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ebafd1adc05a751215ae959f2891752">sparc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a069fe14c1b6db6a31124817f2e57c954">sparcel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a34e8fe940082d534b3957f06616c8227">sparcv9</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a475e7f13c36b181edba29cfcca212def">spir</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5973589725994222a16112b960c74323">spir64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aeee38b63a639e89548c0efc74cab3b65">spirv</a>, <a href="#a547abd13f7a3c063aa72c8192a868154afc429c7efea3699ead2afe26b7db09df">spirv32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae0a08d9852914cec82b405e32e87fbdc">spirv64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">systemz</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ad7837c42372169017a6e5ff3eaa42d1d">tce</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8f07c386f3b82ef15a54318946248f96">tcele</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">thumb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a038a23cbd1756bf797c083c48229dcfd">thumbeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">UnknownArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a419abb6aa1b60e8d534b06311c1e553c">ve</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ac0478f40eaacc5f340e93827756e7a33">wasm32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ad6b7ed7027706d2960e771c6374025b1">wasm64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">x86</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">x86_64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a1e3f00d3a8c8c59f0f95fd80f1d3ba53">xcore</a> and <a href="#a547abd13f7a3c063aa72c8192a868154ab9cc677b26266a0658a4f6feb4ee0bdc">xtensa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a93afe3b7548a63fa4d20b50bedb0a61a">llvm::orc::checkMachORelocatableObject</a> and <a href="#a19adff7744a0fe75c2c083e6d9b710e1">getArchName</a>.</p>

</div>
</div>

### getArchTypePrefix {#af6f1d6df1b516f446668f876f6c37b29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Triple::getArchTypePrefix (<a href="#a547abd13f7a3c063aa72c8192a868154">ArchType</a> Kind)</td>
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

<p>Get the "prefix" canonical name for the <span class="doxyComputerOutput">Kind</span> architecture.</p>


<p>This is the prefix used by the architecture specific builtins, and is suitable for passing to</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a7625b4659e0bcfd1e8938bfc188537c4">Intrinsic::getIntrinsicForClangBuiltin()</a>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- The architecture prefix, or 0 if none is defined.</p></dd>
</dl>


<p>Declaration at line 1244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">aarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">aarch64_32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">aarch64_be</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">amdgcn</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5ea1b051c09d0127f2d90e0ad6b487df">amdil</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ade794c636782fc46854cb047c40c164b">amdil64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aed5f38c6bd089f09c02aae8072ceb514">arc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">arm</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af65ab1964be676bea302940a45765021">armeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9b780628857be980e628bf44ae7dce56">avr</a>, <a href="#a547abd13f7a3c063aa72c8192a868154abccdd747b05d7cfff6ae937ffdf5ba03">bpfeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a83d003d0efa0cd997646dc0343d7093f">bpfel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a21a4eb647191d4bd084ffdd749dd9100">csky</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ca957896440ddfeeedda9c05723c150">dxil</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5770b66a2436004885ac116a8ac357d5">hexagon</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aca408a723390395eeaa343d8f1e307c4">hsail</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a74533b62667da81390b35d2a47709458">hsail64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5c48161b8fa1243dfab0169510c72bb1">kalimba</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8ccdc49befcb57d683a4ed2025a7f60d">lanai</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0c64155961d19dceb44b43f5a9992d1a">loongarch32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">loongarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae3dbf1f961e0618ea793bc9c099b932a">m68k</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">mips</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">mips64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">mips64el</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">mipsel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae06ff88d5da98b63a6b4397fcb7a6050">nvptx</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a92ac53f0fca7e6c3f4e56a2d4903b9ae">nvptx64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">ppc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">ppc64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">ppc64le</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">ppcle</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a060ea888d89f5d59a5743118e429296f">r600</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae84559483d0c0f2bddc802ce6f76dd8b">riscv32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08">riscv64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a396b3f1df93fc8cb904b66759a0d1a96">shave</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ebafd1adc05a751215ae959f2891752">sparc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a069fe14c1b6db6a31124817f2e57c954">sparcel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a34e8fe940082d534b3957f06616c8227">sparcv9</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a475e7f13c36b181edba29cfcca212def">spir</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5973589725994222a16112b960c74323">spir64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aeee38b63a639e89548c0efc74cab3b65">spirv</a>, <a href="#a547abd13f7a3c063aa72c8192a868154afc429c7efea3699ead2afe26b7db09df">spirv32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae0a08d9852914cec82b405e32e87fbdc">spirv64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">systemz</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">thumb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a038a23cbd1756bf797c083c48229dcfd">thumbeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a419abb6aa1b60e8d534b06311c1e553c">ve</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ac0478f40eaacc5f340e93827756e7a33">wasm32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ad6b7ed7027706d2960e771c6374025b1">wasm64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">x86</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">x86_64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a1e3f00d3a8c8c59f0f95fd80f1d3ba53">xcore</a> and <a href="#a547abd13f7a3c063aa72c8192a868154ab9cc677b26266a0658a4f6feb4ee0bdc">xtensa</a>.</p>

</div>
</div>

### getEnvironmentTypeName {#abb703efa7aa5bddf5875fe8f2517e787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Triple::getEnvironmentTypeName (<a href="#a1778f5c464f88710033f7e11e84a9324">EnvironmentType</a> Kind)</td>
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

<p>Get the canonical name for the <span class="doxyComputerOutput">Kind</span> environment.</p>

<p>Declaration at line 1253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a1778f5c464f88710033f7e11e84a9324ab926bec66aeb0288525973f203bcb94a">Amplification</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a0ceb06180ab5fc86e9ad27563b538439">Android</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ab73388cc76387a636177ac9e405d0b39">AnyHit</a>, <a href="#a1778f5c464f88710033f7e11e84a9324adf4a58c1d4eb1aeba280a3fc580e9f8d">Callable</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a783d818fcc0a9d1e095674aa7b255082">ClosestHit</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ace5d58a24effb264483f4af8b79b97b2">CODE16</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a35a7d7865588f76c4f300fb1f07ee1bc">Compute</a>, <a href="#a1778f5c464f88710033f7e11e84a9324afcb832e2cb16856e53500d3c1e52a890">CoreCLR</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a0521408131ca98c3ee4f486df216ea39">Cygnus</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a9250a1f506b7407b838bf0b494f9cd33">Domain</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a847a953f3f994ab5453f075cea9ca7af">EABI</a>, <a href="#a1778f5c464f88710033f7e11e84a9324af2b02c10c51141fdaa4cb49402e20169">EABIHF</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ade3aad57a34a47654ebeee1a2d4ab960">Geometry</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ae6c91532448c0be7978cf1bfcdaa11bb">GNU</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a21e1198b41cc86aafe10fcd5a6ca330b">GNUABI64</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a75fa362b8315ce952fde83ff09a4c599">GNUABIN32</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a73b4a675dd734e1efcab33de0d217a37">GNUEABI</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a699fcd7db202863a2a82143681dadb85">GNUEABIHF</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ae5c77cfc976654fac7f3f50ee1352a8e">GNUEABIHFT64</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a2343e70ca8369c9a61e3e25aa4e08216">GNUEABIT64</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a61ce851e1f60ad25421987629f5ac2c2">GNUF32</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a587bfd81081ee91855e23c7cc05d4487">GNUF64</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a0a05a130bb4b1c97244ff98d64e0de5d">GNUILP32</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a9953bc1a6bb23d4a733faf9afb0df99a">GNUSF</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a648404ce7e68eb5d5a6c60afa8744438">GNUT64</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ab0c4c38b98e3b1482fc1c5afc8649e28">GNUX32</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ac8bc9b9934c75b722dcdde3b705c0a51">Hull</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ac5ff0a8f8e278b84cdd8518a6e0c67d8">Intersection</a>, <a href="#a1778f5c464f88710033f7e11e84a9324aa97aa42b85b1502e458177c354ab6788">Itanium</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a38ed328b8551b06c5a133e54867110bf">Library</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a40176fd51bd652566e1d48b5455fd081">LLVM</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a0a522a127e133d8cd07fa678e6672695">MacABI</a>, <a href="#a1778f5c464f88710033f7e11e84a9324aa1a97c079fbb80fcd9ab0f5fa24f3025">Mesh</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ad6c99823a0c7477c6412728485bb0fe7">Miss</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a6d53dbdf9a8b9b1092558cf23f83a95a">MSVC</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a332336ad935952ff734309ce432de6d1">Musl</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a27355a1eadfe9594a7acc5634d54bfc8">MuslABI64</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a07818ec9990bfc4675291f2235ab6e8b">MuslABIN32</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a8a7dd3fc84b97dc5b1a677d60e46df80">MuslEABI</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ab711c5b8f1cd078c75864af125d07fef">MuslEABIHF</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a66008454cd4031dad58b64c0eae7f9e4">MuslF32</a>, <a href="#a1778f5c464f88710033f7e11e84a9324aff5daa73e757da85e8803ea0e323d5b0">MuslSF</a>, <a href="#a1778f5c464f88710033f7e11e84a9324ae2e0845b94acce4ef8966096195201dd">MuslX32</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a8a0496f998fd9139553edc0ef61c2cc4">OpenCL</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a582eb6a495698055109b21d02b959c2e">OpenHOS</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a74151519e4fd7f222963d600ad2d44b5">PAuthTest</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a4bd403d91c4535171833f92e0ce36137">Pixel</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a15bc4c083c1cda54e3011297b4bf8351">RayGeneration</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a587146bd8be66f0980d55ca2664c5642">Simulator</a>, <a href="#a1778f5c464f88710033f7e11e84a9324a6c32bcd90dff79307baf3147697ae1d3">UnknownEnvironment</a> and <a href="#a1778f5c464f88710033f7e11e84a9324a71b983b2a1bf8a46c5ac7d21de26fb4a">Vertex</a>.</p>


<p>Referenced by <a href="#ade97ab011dc19854c9886f2c6d8ecc66">getEnvironmentVersionString</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/modulemetadatainfo/#a89522dcd8c7e60779d4d260b48f921d6">llvm::dxil::ModuleMetadataInfo::print</a>, <a href="#a472091dc314efebea60a6c5cff416cc9">setEnvironment</a>, <a href="#a0e2cea374a7428eb1b5ec87ef774e552">setObjectFormat</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a52ad1f2fa223473029d3b3535029d7e5">translateMetadata</a>.</p>

</div>
</div>

### getObjectFormatTypeName {#ada671e44e91b68a18f8a61f12dd1f475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Triple::getObjectFormatTypeName (<a href="#a83e907e55fa50e093caa96a0aff96201">ObjectFormatType</a> ObjectFormat)</td>
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

<p>Get the name for the <span class="doxyComputerOutput">Object</span> format.</p>

<p>Declaration at line 1256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a83e907e55fa50e093caa96a0aff96201aa943abc041caa1cc4c074bbf38b76267">COFF</a>, <a href="#a83e907e55fa50e093caa96a0aff96201a382f97aab858a35311f657a88f998a68">DXContainer</a>, <a href="#a83e907e55fa50e093caa96a0aff96201a456b64e26b8bcdbd8294689615d8a055">ELF</a>, <a href="#a83e907e55fa50e093caa96a0aff96201a7d71851eea2209e547ae06c9c03768f5">GOFF</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a83e907e55fa50e093caa96a0aff96201a2ed78f59e2d35011e1d1ed0ad96cf411">MachO</a>, <a href="#a83e907e55fa50e093caa96a0aff96201ae057411e10951f5a7dc545e6199c5490">SPIRV</a>, <a href="#a83e907e55fa50e093caa96a0aff96201af2f88d8b470958614a01866d4714b5a4">UnknownObjectFormat</a>, <a href="#a83e907e55fa50e093caa96a0aff96201a660d4029da29691e97daf8c8aabb1ffb">Wasm</a> and <a href="#a83e907e55fa50e093caa96a0aff96201a1f7d761ca747e66d2ac0caa0d54b1824">XCOFF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad059d61cab7f6bc8ee555ae23acd7b52">llvm::orc::enableDebuggerSupport</a>, <a href="#ade97ab011dc19854c9886f2c6d8ecc66">getEnvironmentVersionString</a>, <a href="#a5c2fb6bace55f9b58ed0ba9fe363299e">normalize</a>, <a href="#a472091dc314efebea60a6c5cff416cc9">setEnvironment</a> and <a href="#a0e2cea374a7428eb1b5ec87ef774e552">setObjectFormat</a>.</p>

</div>
</div>

### getOSTypeName {#a8192d4072e4aaba803248250d1faf61c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Triple::getOSTypeName (<a href="#a3cfefc755ab656000934f91193afb1cd">OSType</a> Kind)</td>
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

<p>Get the canonical name for the <span class="doxyComputerOutput">Kind</span> operating system.</p>

<p>Declaration at line 1250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a3cfefc755ab656000934f91193afb1cda55c9e8cff2a0eab89d1b234d419ee93f">AIX</a>, <a href="#a3cfefc755ab656000934f91193afb1cda0a0dddcf03f8f66f7c13558b3c81d845">AMDHSA</a>, <a href="#a3cfefc755ab656000934f91193afb1cda7d8eb2c700c876375f588d68dc692f15">AMDPAL</a>, <a href="#a3cfefc755ab656000934f91193afb1cdac1302c2bd5aa5a28b3558b748e57e6ea">BridgeOS</a>, <a href="#a3cfefc755ab656000934f91193afb1cdac81124e2bdd6fb0d7b3fc4bd30233928">CUDA</a>, <a href="#a3cfefc755ab656000934f91193afb1cda0824a8c56de913d60c6f55edc0ac3148">Darwin</a>, <a href="#a3cfefc755ab656000934f91193afb1cda0e7175bb9a8eea9efd2a5e50b6ca84ab">DragonFly</a>, <a href="#a3cfefc755ab656000934f91193afb1cda600aa0b72f321a0cdf0e4b3f38b9b6c8">DriverKit</a>, <a href="#a3cfefc755ab656000934f91193afb1cdaea39dbcca2c32c044d958aceb371bb13">ELFIAMCU</a>, <a href="#a3cfefc755ab656000934f91193afb1cdae7c70b9eb6106c04f131eca1e3be44ac">Emscripten</a>, <a href="#a3cfefc755ab656000934f91193afb1cda64fc6929b84f845ced55d3313ebcf423">FreeBSD</a>, <a href="#a3cfefc755ab656000934f91193afb1cdaad44ff9454db9e8eb2e38d964f0345b7">Fuchsia</a>, <a href="#a3cfefc755ab656000934f91193afb1cda55732429424dd801e57c7c667a8d4217">Haiku</a>, <a href="#a3cfefc755ab656000934f91193afb1cda5523c4eadf302b516ae738ddf52076a5">HermitCore</a>, <a href="#a3cfefc755ab656000934f91193afb1cdaf17d175b40b8e7ceedc92aea3929eb27">Hurd</a>, <a href="#a3cfefc755ab656000934f91193afb1cdafad6e6763679be1478d9283a7344d243">IOS</a>, <a href="#a3cfefc755ab656000934f91193afb1cda6506444610ddf1a927cf919508b2ea1b">KFreeBSD</a>, <a href="#a3cfefc755ab656000934f91193afb1cda76d4dd8dc67e3a11d975743f6d63a9df">Linux</a>, <a href="#a3cfefc755ab656000934f91193afb1cdaf7d25a9254177b6890fd8c115503014d">LiteOS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a3cfefc755ab656000934f91193afb1cda379ed41d00eaa4c446cdefc892d8762f">Lv2</a>, <a href="#a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075">MacOSX</a>, <a href="#a3cfefc755ab656000934f91193afb1cda81cc47a265b37fea8b5b3575b67ea6ed">Mesa3D</a>, <a href="#a3cfefc755ab656000934f91193afb1cdaae17c480f3a0e37421e04400dca90d1b">NaCl</a>, <a href="#a3cfefc755ab656000934f91193afb1cdad10d236fcf52bdbf36bd6b401ca9e427">NetBSD</a>, <a href="#a3cfefc755ab656000934f91193afb1cda6f69427cfc546c2402cdbee116ca6af9">NVCL</a>, <a href="#a3cfefc755ab656000934f91193afb1cda13c01bda5d01cb2264a0cebe7b411c54">OpenBSD</a>, <a href="#a3cfefc755ab656000934f91193afb1cda63d6dc93c7b6ab41ba169620a639bec1">PS4</a>, <a href="#a3cfefc755ab656000934f91193afb1cda683700aa7afbff16fe3885d5ad05923c">PS5</a>, <a href="#a3cfefc755ab656000934f91193afb1cda638da1f392b8b391c2af80e9d461d17b">RTEMS</a>, <a href="#a3cfefc755ab656000934f91193afb1cda3abcbc3caa438ea915121cdf3d373aae">Serenity</a>, <a href="#a3cfefc755ab656000934f91193afb1cdac4081e09efdc53c28fc78e5ca68ea70a">ShaderModel</a>, <a href="#a3cfefc755ab656000934f91193afb1cdac44628c2fbd9505dc608a330838fccce">Solaris</a>, <a href="#a3cfefc755ab656000934f91193afb1cda2838cf6df0f09591c50d752d46c4350d">TvOS</a>, <a href="#a3cfefc755ab656000934f91193afb1cda7af47f8e02ca8bd701e40ba03b2bcd95">UEFI</a>, <a href="#a3cfefc755ab656000934f91193afb1cda4b110a50637320a1a0db33999b809ddd">UnknownOS</a>, <a href="#a3cfefc755ab656000934f91193afb1cda844b53b7eb8188bdea24d4147b10d2b3">Vulkan</a>, <a href="#a3cfefc755ab656000934f91193afb1cdab4b12e4f268dff8ead7f9194ee8da04b">WASI</a>, <a href="#a3cfefc755ab656000934f91193afb1cda87a3c8454473c64f6d605ebd757759ad">WatchOS</a>, <a href="#a3cfefc755ab656000934f91193afb1cdafd0c0a465dca43ad44f79806a226a1ae">Win32</a>, <a href="#a3cfefc755ab656000934f91193afb1cdabb5225659a201976ce2594df579e3623">XROS</a> and <a href="#a3cfefc755ab656000934f91193afb1cdafd36ac5f07b0474e2b5c167ab7158538">ZOS</a>.</p>


<p>Referenced by <a href="#a024faa768c9d7b624a68980113f92693">getOSVersion</a> and <a href="#aadd45e5c167eb85f1741ee869ea790e8">setOS</a>.</p>

</div>
</div>

### getVendorTypeName {#a298fc373d25fb899e8963abf7f88e2e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Triple::getVendorTypeName (<a href="#a96fe35195867c94aef1adf2ad0e20eec">VendorType</a> Kind)</td>
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

<p>Get the canonical name for the <span class="doxyComputerOutput">Kind</span> vendor.</p>

<p>Declaration at line 1247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a96fe35195867c94aef1adf2ad0e20eeca77be73c19a4451fa0580ac5b9018357b">AMD</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eeca674d908c8b0ebe1880f8c8d651eda9e2">Apple</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eecaf2892bfd7e664cbdc7ced8ae9c15ca33">CSR</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eeca919656f12c161f60c585b6ea65c77f9a">Freescale</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eecae7589347388e13a416edcb71a946416c">IBM</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eeca9e259de1548e02615004c538112d3aab">ImaginationTechnologies</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eecac949231cdefe4cbb0f48febd5fda4ce7">Intel</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eecaa29f6dfe49ede82d55ad9310efd3582c">Mesa</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eecadc6b40589adfbd4756bf72561c69a8c3">MipsTechnologies</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eecaeb014b23b113a1cda5058e4e31aca881">NVIDIA</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eeca5881a9306181e4330e92688656a52f4c">OpenEmbedded</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eecafbca4de1e7e0ce699db11feb6a205b32">PC</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eecaf8cf55a2ccb688a02134bd768c9a1a3d">SCEI</a>, <a href="#a96fe35195867c94aef1adf2ad0e20eeca841dde16a0ee702c5b7aeda162c85e0c">SUSE</a> and <a href="#a96fe35195867c94aef1adf2ad0e20eeca0f632276cf5b78ab97257d7f90b7f97f">UnknownVendor</a>.</p>


<p>Referenced by <a href="#af96094469e937492a76dd8e01e81e7cc">setVendor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Static helpers for converting alternate architecture names.

### getArchTypeForLLVMName {#a5d5efe3bb966ce825560b2e6dd46f8ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ArchType Triple::getArchTypeForLLVMName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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

<p>The canonical type for the given LLVM architecture name (e.g., "x86").</p>

<p>Declaration at line 1263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">aarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">aarch64_32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">aarch64_be</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">amdgcn</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5ea1b051c09d0127f2d90e0ad6b487df">amdil</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ade794c636782fc46854cb047c40c164b">amdil64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aed5f38c6bd089f09c02aae8072ceb514">arc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">arm</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af65ab1964be676bea302940a45765021">armeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9b780628857be980e628bf44ae7dce56">avr</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a21a4eb647191d4bd084ffdd749dd9100">csky</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ca957896440ddfeeedda9c05723c150">dxil</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5770b66a2436004885ac116a8ac357d5">hexagon</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aca408a723390395eeaa343d8f1e307c4">hsail</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a74533b62667da81390b35d2a47709458">hsail64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5c48161b8fa1243dfab0169510c72bb1">kalimba</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8ccdc49befcb57d683a4ed2025a7f60d">lanai</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0c64155961d19dceb44b43f5a9992d1a">loongarch32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">loongarch64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae3dbf1f961e0618ea793bc9c099b932a">m68k</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">mips</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">mips64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">mips64el</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">mipsel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a752f0f4d07cf7dcdbe539a95dfe4cbff">msp430</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae06ff88d5da98b63a6b4397fcb7a6050">nvptx</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a92ac53f0fca7e6c3f4e56a2d4903b9ae">nvptx64</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#aabf4024742648721f7840ae35fe7ffd8">parseBPFArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">ppc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">ppc64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">ppc64le</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">ppcle</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a060ea888d89f5d59a5743118e429296f">r600</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a863d4793e08f6a5a3ca20149b3e7a85d">renderscript32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a1c43e5f860c9e21dab6fcfc65f93945d">renderscript64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae84559483d0c0f2bddc802ce6f76dd8b">riscv32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08">riscv64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a396b3f1df93fc8cb904b66759a0d1a96">shave</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a9ebafd1adc05a751215ae959f2891752">sparc</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a069fe14c1b6db6a31124817f2e57c954">sparcel</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a34e8fe940082d534b3957f06616c8227">sparcv9</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a475e7f13c36b181edba29cfcca212def">spir</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5973589725994222a16112b960c74323">spir64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154aeee38b63a639e89548c0efc74cab3b65">spirv</a>, <a href="#a547abd13f7a3c063aa72c8192a868154afc429c7efea3699ead2afe26b7db09df">spirv32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ae0a08d9852914cec82b405e32e87fbdc">spirv64</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a88e653a89d15149cc7a68f88be360303">llvm::StringSwitch&lt; T, R &gt;::StartsWith</a>, <a href="#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">systemz</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ad7837c42372169017a6e5ff3eaa42d1d">tce</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a8f07c386f3b82ef15a54318946248f96">tcele</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">thumb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a038a23cbd1756bf797c083c48229dcfd">thumbeb</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">UnknownArch</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a419abb6aa1b60e8d534b06311c1e553c">ve</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ac0478f40eaacc5f340e93827756e7a33">wasm32</a>, <a href="#a547abd13f7a3c063aa72c8192a868154ad6b7ed7027706d2960e771c6374025b1">wasm64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">x86</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">x86_64</a>, <a href="#a547abd13f7a3c063aa72c8192a868154a1e3f00d3a8c8c59f0f95fd80f1d3ba53">xcore</a> and <a href="#a547abd13f7a3c063aa72c8192a868154ab9cc677b26266a0658a4f6feb4ee0bdc">xtensa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a9a9a7989eeb174879ae8581e33e61824">llvm::TargetRegistry::lookupTarget</a> and <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a7ef5bb146eb2c0e3a609a6a169ac4f44">llvm::EngineBuilder::selectTarget</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">Triple.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
