---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/globalvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GlobalValue` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::GlobalValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an important base class in LLVM. <a href="/web-llvm/docs/api/classes/llvm/constant/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3af0428ec6e48cb2f05c199b7b9f7e07">GUID</a> = uint64_t</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Declare a type to represent a global unique identifier for a global value. <a href="#a3af0428ec6e48cb2f05c199b7b9f7e07">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">LinkageTypes { <a href="#aedfa75f0c85c4aa85b257f066fbea57c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An enumeration for the kinds of linkage for global values. <a href="#aedfa75f0c85c4aa85b257f066fbea57c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">VisibilityTypes { <a href="#a9141f967188383108a69cc1b8ed3c195">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An enumeration for the kinds of visibility of global values. <a href="#a9141f967188383108a69cc1b8ed3c195">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DLLStorageClassTypes { <a href="#a6948096330886cc831391c75adbadaf8">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Storage classes of global values for PE targets. <a href="#a6948096330886cc831391c75adbadaf8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ThreadLocalMode { <a href="#a05c6b3b9372b56d130e005db4837da62">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">UnnamedAddr { <a href="#ae8df4be75bfc50b1eadd74e85c25fa45">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6beea678d6a163206b1ef36b1a59a02">GlobalValue</a> (const GlobalValue &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a> (Type *Ty, ValueTy VTy, AllocInfo AllocInfo, LinkageTypes Linkage, const Twine &amp;Name, unsigned AddressSpace)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbca9233f5cc59714d6bb6afe39ef9fa">~GlobalValue</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a702d4986803a1782ba305b1c7a0f1c21">getAddressSpace</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac18f876b955434599bd93fd50aad53b8">hasGlobalUnnamedAddr</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaef9bedb9a16483f04717a57af933173">hasAtLeastLocalUnnamedAddr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this value's address is not significant in this module. <a href="#aaef9bedb9a16483f04717a57af933173">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae8df4be75bfc50b1eadd74e85c25fa45">UnnamedAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2417a3c6edd0db7a9ad84b82c4054b7">getUnnamedAddr</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38c97622dccff7ae31fe0be3b21c9b3d">setUnnamedAddr</a> (UnnamedAddr Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9e5c8e6f11bf0df2b3e220bb6557418">hasComdat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43721e1e88567116e8fca545125d86bf">getComdat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c3037bc9ccfd4637b88bc8281a4f889">getComdat</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9141f967188383108a69cc1b8ed3c195">VisibilityTypes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b9561d9ef3d237ef894023187fa26c">getVisibility</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e6237ebf8cf834ae6fa726efccaef8d">hasDefaultVisibility</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50baaf8d8a18c0cda69eb8d8eca178f9">hasHiddenVisibility</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6d775e717aaa2d1916bccb2ff8778e9">hasProtectedVisibility</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa242d8ab89216c14beab812e07009b2a">setVisibility</a> (VisibilityTypes V)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a239427c2c3a01e23bd15b29633696536">isThreadLocal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the value is "Thread Local", its value isn't shared by the threads. <a href="#a239427c2c3a01e23bd15b29633696536">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef4a60d204c56d074163c4c3a70bc603">setThreadLocal</a> (bool Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a472652f9e89e006426f371fcbfa6f619">setThreadLocalMode</a> (ThreadLocalMode Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a05c6b3b9372b56d130e005db4837da62">ThreadLocalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52126ae2091b18cecfd5ad0f0012839a">getThreadLocalMode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6948096330886cc831391c75adbadaf8">DLLStorageClassTypes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af09a662b4e302d0683d0fe9dc2a9335f">getDLLStorageClass</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66501d6d43642a526ab769458d700aa4">hasDLLImportStorageClass</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a94ead7cfc2b5b3c035be6fe7b52a4f">hasDLLExportStorageClass</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c699aba3d6b469357ef0b4e1aa2580">setDLLStorageClass</a> (DLLStorageClassTypes C)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f52d196211845d0d605733e2f699055">hasSection</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7215706ede5f29b81e4f99af35e87aa6">getSection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a913a5d4b2cddde762446bd494e81a3f2">getType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global values are always pointers. <a href="#a913a5d4b2cddde762446bd494e81a3f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1dd2acfc2950742e41a64a342b15c80">getValueType</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2df2f2e94b5493e9434dbf1c483dbc72">isImplicitDSOLocal</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78c4d0538c7dbffa955486abae2b61bb">setDSOLocal</a> (bool Local)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19db81b6f3d3ab342972dce7756fb077">isDSOLocal</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bf930687efa9a6cdc47d318dbd2e6d4">hasPartition</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72237a63b5edcf78a32453822139f1d5">getPartition</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff8740863a5ee2650339400236b6224b">setPartition</a> (StringRef Part)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d863ff0d778248ac9b693db3494565c">hasSanitizerMetadata</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/globalvalue/sanitizermetadata">SanitizerMetadata</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10dbf1e2be9c60af49efb9bfded99225">getSanitizerMetadata</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add48ed79a5cd63c7165f3f4da102b9fd">setSanitizerMetadata</a> (SanitizerMetadata Meta)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b8db417ccdc447464add1a3d9358759">removeSanitizerMetadata</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f4c146a2651316c36059560e138d3e9">setNoSanitizeMetadata</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40631ccf8ca06c1942f13f4872ed8e86">isTagged</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a008adb117253c7a0dde2f796be489d65">isDefinitionExact</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the currently visible definition of this global (if any) is exactly the definition we will see at runtime. <a href="#a008adb117253c7a0dde2f796be489d65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52355f8a15cd7cedfe83bd82b59e942a">hasExactDefinition</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this global has an exact defintion. <a href="#a52355f8a15cd7cedfe83bd82b59e942a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1558e13ceef68db8ea9f4e3b5a64cbd">isInterposable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this global's definition can be substituted with an <em>arbitrary</em> definition at link time or load time. <a href="#aa1558e13ceef68db8ea9f4e3b5a64cbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa63851a5f68b64cf93d3f8c4a973f33d">canBenefitFromLocalAlias</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1847e956a0087fefdb49e2a9583c7d18">hasExternalLinkage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae76e0b39c563b63554b4c99a8ad726e4">hasAvailableExternallyLinkage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a091e6599599c4e668373e0feefa92c01">hasLinkOnceLinkage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3acdc3a8bbb5f15edd761e8aee3e2dfd">hasLinkOnceAnyLinkage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae28d149d03a6ae88267f649bc1dbe42c">hasLinkOnceODRLinkage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca0b3e9845b2fa35c965edaabd5c6bc">hasWeakLinkage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61afb04130343acdd861174587400c10">hasWeakAnyLinkage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab241086cb8a1e3f7e77fb00c9a8aeb2e">hasWeakODRLinkage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac90734e1bc3dc440f2db27f4c38a4f43">hasAppendingLinkage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc292fc6d075e3ed6e68b0866ec3524">hasInternalLinkage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ed4c5535997ad77ffee00f92430b576">hasPrivateLinkage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ba1af4b9d9faa4a33729bbbecee83d1">hasLocalLinkage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51af265dc931258cdb8ffb37ee6decee">hasExternalWeakLinkage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac10ac4576e030b231e1fbb5a8272f01f">hasCommonLinkage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a334704e7c859bd7c44ca86249a6280cc">hasValidDeclarationLinkage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a687973de03d041e04b50a76d19d4fd36">setLinkage</a> (LinkageTypes LT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a863b49cf36a53aa979a81c6e10c4d6b5">isDiscardableIfUnused</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0495132fc83c026033c62c59b30489f">isWeakForLinker</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed99d84162082a52cd08efb7dfe017e4">getGlobalIdentifier</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the modified name for this global value suitable to be used as the key for a global lookup (e.g. <a href="#aed99d84162082a52cd08efb7dfe017e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3af0428ec6e48cb2f05c199b7b9f7e07">GUID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71ee7e63264e4997a3340a781d44832e">getGUID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a 64-bit global unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> constructed from global value name (i.e. <a href="#a71ee7e63264e4997a3340a781d44832e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32e606ac4c88f71f14212e42b808e7f4">isDeclaration</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the primary definition of this global value is outside of the current translation unit. <a href="#a32e606ac4c88f71f14212e42b808e7f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b66f492cbea5f4b4f434d7178477116">isDeclarationForLinker</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a904b8b68c7e4e888158b03f0eae0e4d5">isStrongDefinitionForLinker</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this global's definition will be the one chosen by the linker. <a href="#a904b8b68c7e4e888158b03f0eae0e4d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a788ede5201dc9b44e419e9fd2fbb38bf">getAliaseeObject</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7017e24bb5f77030be934b76de3f58a4">getAliaseeObject</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3edc4a0cb9df73b6f94a21a51d3c8cf0">isAbsoluteSymbolRef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether this is a reference to an absolute symbol. <a href="#a3edc4a0cb9df73b6f94a21a51d3c8cf0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7918bda9a2e43bf56739cfe8c3d92803">getAbsoluteSymbolRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is an absolute symbol reference, returns the range of the symbol, otherwise returns std::nullopt. <a href="#a7918bda9a2e43bf56739cfe8c3d92803">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae52ff267989fb6aca697d29dea0cb027">removeFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method unlinks 'this' from the containing module, but does not delete it. <a href="#ae52ff267989fb6aca697d29dea0cb027">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c733400ba8d113fd2976d4fea0db981">eraseFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method unlinks 'this' from the containing module and deletes it. <a href="#a7c733400ba8d113fd2976d4fea0db981">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a739b30c811f1eece61b05320ddf44e5b">getParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the module that this global value is contained inside of... <a href="#a739b30c811f1eece61b05320ddf44e5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a3012859837d61e5de0037879333749">getParent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5d2c67dadc073dac78224224ee89350">getDataLayout</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the data layout of the module this global belongs to. <a href="#aa5d2c67dadc073dac78224224ee89350">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3a42354a5b89aa8ade55dab229036f6">canBeOmittedFromSymbolTable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if GV can be left out of the object symbol table. <a href="#ae3a42354a5b89aa8ade55dab229036f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf6a02ecb2b904406b783da5bfd6564e">getGlobalValueSubClassData</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4e766c05dc79278ee675263c13c1cb0">setGlobalValueSubClassData</a> (unsigned V)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61c5cb86cc6dbf8bf883170689b421a7">setParent</a> (Module *parent)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96c9558e69f588728273b57eb5a1fe73">copyAttributesFrom</a> (const GlobalValue *Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy all additional attributes (those not needed to create a <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a>) from the <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> Src to this one. <a href="#a96c9558e69f588728273b57eb5a1fe73">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ad45ad67b9df38e12261c3675e9824c">destroyConstantImpl</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Override destroyConstantImpl to make sure it doesn't get called on <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a>'s because they shouldn't be treated like other constants. <a href="#a2ad45ad67b9df38e12261c3675e9824c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12aa05338951522d7c3936a091f4704a">handleOperandChangeImpl</a> (Value *From, Value *To)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68b1bf0587e314cad8ab83618f9d9bad">mayBeDerefined</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the definition of this global may be replaced by a differently optimized variant of the same source level function at link time. <a href="#a68b1bf0587e314cad8ab83618f9d9bad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94dab11fc3e2662aac0663913381551f">isNobuiltinFnDef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the global is a function definition with the nobuiltin attribute. <a href="#a94dab11fc3e2662aac0663913381551f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a177d1baba701de456c801ac1c05979b9">ValueType</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b20bb41f6274a04399a83a821869ad1">Visibility</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8c3ae3e5e774d859ca9b52521a537af">UnnamedAddrVal</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af89f25d8a89068ab9be05f2a095da4ed">DllStorageClass</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf0096839ddf4913784dfaa716329064">ThreadLocal</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53750bb517b7bfc28013f16cdbe2de4d">HasLLVMReservedName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the function's name starts with "llvm.". <a href="#a53750bb517b7bfc28013f16cdbe2de4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbf8c73bfeef429bbf6f5d1ae346893b">IsDSOLocal</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If true then there is a definition within the same linkage unit and that definition cannot be runtime preempted. <a href="#abbf8c73bfeef429bbf6f5d1ae346893b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b2401e912b1044a4baf7a5a926968e4">HasPartition</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this symbol has a partition name assigned (see <a href="https://lld.llvm.org/Partitions.html">https://lld.llvm.org/Partitions.html</a>). <a href="#a1b2401e912b1044a4baf7a5a926968e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07e6feb9f188917f8dc965f78317f181">HasSanitizerMetadata</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this symbol has sanitizer metadata available. <a href="#a07e6feb9f188917f8dc965f78317f181">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fb893b6154100a981579b7b5cb3e638">IntID</a> = (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a>)0U</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The intrinsic <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for this subclass (which must be a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>). <a href="#a4fb893b6154100a981579b7b5cb3e638">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb71c8012dfaa189618d2cdafb58b4b0">Parent</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eaf291fe2fbdfea96c16bc681162aa7">SubClassData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ae8df4be75bfc50b1eadd74e85c25fa45">UnnamedAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e8300b59be44b0c7913ae50fd5c487e">getMinUnnamedAddr</a> (UnnamedAddr A, UnnamedAddr B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac00103d63c269693fe360702dd9142d7">getLinkOnceLinkage</a> (bool ODR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1a929646bd99aa881cff849f40da718">getWeakLinkage</a> (bool ODR)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89a664b58385307fbb24c02e141d864b">isExternalLinkage</a> (LinkageTypes Linkage)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a578061260691a59a9e7b0455fd68359c">isAvailableExternallyLinkage</a> (LinkageTypes Linkage)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dc5c71cdefd415dcc8569ae3f2b7892">isLinkOnceAnyLinkage</a> (LinkageTypes Linkage)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4663ee02ad0f28a78539ec85c91bec0">isLinkOnceODRLinkage</a> (LinkageTypes Linkage)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f4d5111c78b4b976e362d12f01ad782">isLinkOnceLinkage</a> (LinkageTypes Linkage)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0918c134c7b8131fa37df98101cd17db">isWeakAnyLinkage</a> (LinkageTypes Linkage)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39cdc71d12722bb912f3a299ab5574ab">isWeakODRLinkage</a> (LinkageTypes Linkage)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad48190a47d8af6ce16465cda531725a9">isWeakLinkage</a> (LinkageTypes Linkage)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b09f704d0928e6811660fa3af8f626c">isAppendingLinkage</a> (LinkageTypes Linkage)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bbb20d12147495c229051feded37cdc">isInternalLinkage</a> (LinkageTypes Linkage)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81812ab49218fff82c3a0c378e0a65b0">isPrivateLinkage</a> (LinkageTypes Linkage)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a308b65a044b4f53e31a2026a81c991d2">isLocalLinkage</a> (LinkageTypes Linkage)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25e8e3490a28e9178b302b76ae643443">isExternalWeakLinkage</a> (LinkageTypes Linkage)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76d750f65089b2e70a927cf9d275a9d7">isCommonLinkage</a> (LinkageTypes Linkage)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a2053e12c56247022b52ffd370ec70d">isValidDeclarationLinkage</a> (LinkageTypes Linkage)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabf6932ed41fc64e17c0030c44eda44e">isInterposableLinkage</a> (LinkageTypes Linkage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the definition of this global may be replaced by something non-equivalent at link time. <a href="#aabf6932ed41fc64e17c0030c44eda44e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcb86d621c23938671ad526d3bd1f9bd">isDiscardableIfUnused</a> (LinkageTypes Linkage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the definition of this global may be discarded if it is not used in its compilation unit. <a href="#adcb86d621c23938671ad526d3bd1f9bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac291102760c543c8e045e829d57d3341">isWeakForLinker</a> (LinkageTypes Linkage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the definition of this global may be replaced at link time. <a href="#ac291102760c543c8e045e829d57d3341">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e999e4bb7297d284f931638721840e5">dropLLVMManglingEscape</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the given string begins with the <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> name mangling escape character '\1', drop it. <a href="#a3e999e4bb7297d284f931638721840e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f44684437922cc04a01fcdcc73215d0">getGlobalIdentifier</a> (StringRef Name, GlobalValue::LinkageTypes Linkage, StringRef FileName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the modified name for a global value suitable to be used as the key for a global lookup (e.g. <a href="#a9f44684437922cc04a01fcdcc73215d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a3af0428ec6e48cb2f05c199b7b9f7e07">GUID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6811428caf500217f319c74e80900c14">getGUID</a> (StringRef GlobalName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a 64-bit global unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> constructed from global value name (i.e. <a href="#a6811428caf500217f319c74e80900c14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeb291fef3614d59a1cb130bb73ab024">classof</a> (const Value *V)</td>
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

## Protected Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a95237a18eb8cdb7f4d1aa99d6120b0">GlobalValueSubClassDataBits</a> = 15</td>
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

## Materialization Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac010bf63f00b00f321a141448942a697">isMaterializable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this function's <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> is being lazily streamed in functions from disk or some other source, this method can be used to check to see if the function has been read in yet or not. <a href="#ac010bf63f00b00f321a141448942a697">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1b5643f40dd3c7b92a548027eb13de0">materialize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make sure this <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> is fully read. <a href="#ac1b5643f40dd3c7b92a548027eb13de0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### GUID {#a3af0428ec6e48cb2f05c199b7b9f7e07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GlobalValue::GUID =  uint64_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Declare a type to represent a global unique identifier for a global value.</p>


<p>This is a 64 bits hash that is used by PGO and ThinLTO to have a compact unique way to identify a symbol.</p>


<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### DLLStorageClassTypes {#a6948096330886cc831391c75adbadaf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::GlobalValue::DLLStorageClassTypes </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Storage classes of global values for PE targets.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DefaultStorageClass<a id="a6948096330886cc831391c75adbadaf8a5354f0f932438b7ec4d5d82d4ec1ae22"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DLLImportStorageClass<a id="a6948096330886cc831391c75adbadaf8aadc8e43e72669932581b5243b4b444b6"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> to be imported from DLL (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DLLExportStorageClass<a id="a6948096330886cc831391c75adbadaf8a81819441fb6de420d4290ac79aaf9dc0"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> to be accessible from DLL (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>

</div>
</div>

### LinkageTypes {#aedfa75f0c85c4aa85b257f066fbea57c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::GlobalValue::LinkageTypes </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An enumeration for the kinds of linkage for global values.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExternalLinkage<a id="aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e"></a></td>
<td class="doxyEnumItemDescription">Externally visible function (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AvailableExternallyLinkage<a id="aedfa75f0c85c4aa85b257f066fbea57caa67f293befacbbf974525116ccf2ff42"></a></td>
<td class="doxyEnumItemDescription">Available for inspection, not emission</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LinkOnceAnyLinkage<a id="aedfa75f0c85c4aa85b257f066fbea57ca5ebf288ceb5bbeb7025564727db6d705"></a></td>
<td class="doxyEnumItemDescription">Keep one copy of function when linking (inline)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LinkOnceODRLinkage<a id="aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c"></a></td>
<td class="doxyEnumItemDescription">Same, but only replaced by something equivalent</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WeakAnyLinkage<a id="aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f"></a></td>
<td class="doxyEnumItemDescription">Keep one copy of named function when linking (weak)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WeakODRLinkage<a id="aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a"></a></td>
<td class="doxyEnumItemDescription">Same, but only replaced by something equivalent</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AppendingLinkage<a id="aedfa75f0c85c4aa85b257f066fbea57ca96ad6314ba9210b223b93dc3e15baf99"></a></td>
<td class="doxyEnumItemDescription">Special purpose, only applies to global arrays</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InternalLinkage<a id="aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5"></a></td>
<td class="doxyEnumItemDescription">Rename collisions when linking (static functions)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PrivateLinkage<a id="aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae"></a></td>
<td class="doxyEnumItemDescription">Like Internal, but omit from symbol table</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExternalWeakLinkage<a id="aedfa75f0c85c4aa85b257f066fbea57caa81fc8db28ac4af45766fbab2e79d466"></a></td>
<td class="doxyEnumItemDescription">ExternalWeak linkage description</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CommonLinkage<a id="aedfa75f0c85c4aa85b257f066fbea57ca08c6a63ca3d9cdb39fb584655bf5c501"></a></td>
<td class="doxyEnumItemDescription">Tentative definitions</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>

</div>
</div>

### ThreadLocalMode {#a05c6b3b9372b56d130e005db4837da62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::GlobalValue::ThreadLocalMode </td>
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
<td class="doxyEnumItemName">NotThreadLocal<a id="a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GeneralDynamicTLSModel<a id="a05c6b3b9372b56d130e005db4837da62a55e32c080bb5217324a597d4fb441660"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LocalDynamicTLSModel<a id="a05c6b3b9372b56d130e005db4837da62ac9f6ea05a2d4cca9e093366042dfa6b8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InitialExecTLSModel<a id="a05c6b3b9372b56d130e005db4837da62a92e26a4a1218d351f5a91e7385a3a320"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LocalExecTLSModel<a id="a05c6b3b9372b56d130e005db4837da62a41529b6e723f5025e59ca9364cf70128"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>

</div>
</div>

### UnnamedAddr {#ae8df4be75bfc50b1eadd74e85c25fa45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::GlobalValue::UnnamedAddr </td>
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
<td class="doxyEnumItemName">None<a id="ae8df4be75bfc50b1eadd74e85c25fa45a6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Local<a id="ae8df4be75bfc50b1eadd74e85c25fa45a509820290d57f333403f490dde7316f4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Global<a id="ae8df4be75bfc50b1eadd74e85c25fa45a4cc6684df7b4a92b1dec6fce3264fac8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>

</div>
</div>

### VisibilityTypes {#a9141f967188383108a69cc1b8ed3c195}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::GlobalValue::VisibilityTypes </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An enumeration for the kinds of visibility of global values.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DefaultVisibility<a id="a9141f967188383108a69cc1b8ed3c195a2491e41d821f1d8fd3958ce3df2fddb2"></a></td>
<td class="doxyEnumItemDescription">The GV is visible (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HiddenVisibility<a id="a9141f967188383108a69cc1b8ed3c195a7eade123587a08e674f2ca72e2443771"></a></td>
<td class="doxyEnumItemDescription">The GV is hidden</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ProtectedVisibility<a id="a9141f967188383108a69cc1b8ed3c195ae1cc9a390520055573d459de25747caa"></a></td>
<td class="doxyEnumItemDescription">The GV is protected</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### Constant {#a5bd16c2fbe755cda66b18d56761038ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#aedfa75f0c85c4aa85b257f066fbea57ca96ad6314ba9210b223b93dc3e15baf99">AppendingLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57caa67f293befacbbf974525116ccf2ff42">AvailableExternallyLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57ca08c6a63ca3d9cdb39fb584655bf5c501">CommonLinkage</a>, <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">ExternalLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57caa81fc8db28ac4af45766fbab2e79d466">ExternalWeakLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">InternalLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57ca5ebf288ceb5bbeb7025564727db6d705">LinkOnceAnyLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">LinkOnceODRLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">PrivateLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">WeakAnyLinkage</a> and <a href="#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">WeakODRLinkage</a>.</p>


<p>Referenced by <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a8a638534b520f72ab7f2c886da739a6c">llvm::GlobalAlias::create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a4e6d4520d4b49c5d66c42219f06f5d9d">llvm::GlobalAlias::DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a6313d8c02c396afb981e61ef25088ff2">llvm::GlobalAlias::getAliasee</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a7666cc7bd9294c7ae9992c41c591e08b">llvm::GlobalAlias::getAliasee</a>, <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a4b5d91825bd05a14280768680626e294">llvm::GlobalAlias::operator=</a> and <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a629a9b41f0b6dfa91f5b0a7ac34f2d1a">llvm::GlobalAlias::setAliasee</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GlobalValue() {#ac6beea678d6a163206b1ef36b1a59a02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GlobalValue::GlobalValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp;)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### GlobalValue() {#af38a8629ae32606b01eacbbd667d831c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GlobalValue::GlobalValue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/value/#af6d11b38374c4f9e6ba3a6407da2dee0">ValueTy</a> VTy, <a href="/web-llvm/docs/api/structs/llvm/user/allocinfo">AllocInfo</a> AllocInfo, <a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, unsigned AddressSpace)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="#a6948096330886cc831391c75adbadaf8a5354f0f932438b7ec4d5d82d4ec1ae22">DefaultStorageClass</a>, <a href="#a9141f967188383108a69cc1b8ed3c195a2491e41d821f1d8fd3958ce3df2fddb2">DefaultVisibility</a>, <a href="#af89f25d8a89068ab9be05f2a095da4ed">DllStorageClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="#a53750bb517b7bfc28013f16cdbe2de4d">HasLLVMReservedName</a>, <a href="#a1b2401e912b1044a4baf7a5a926968e4">HasPartition</a>, <a href="#a07e6feb9f188917f8dc965f78317f181">HasSanitizerMetadata</a>, <a href="#abbf8c73bfeef429bbf6f5d1ae346893b">IsDSOLocal</a>, <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>, <a href="#ae8df4be75bfc50b1eadd74e85c25fa45a6adf97f83acf6453d4a6a4b1070f3754">None</a>, <a href="#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">NotThreadLocal</a>, <a href="#a687973de03d041e04b50a76d19d4fd36">setLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>, <a href="#acf0096839ddf4913784dfaa716329064">ThreadLocal</a>, <a href="#af8c3ae3e5e774d859ca9b52521a537af">UnnamedAddrVal</a>, <a href="#a177d1baba701de456c801ac1c05979b9">ValueType</a> and <a href="#a4b20bb41f6274a04399a83a821869ad1">Visibility</a>.</p>


<p>Referenced by <a href="#a96c9558e69f588728273b57eb5a1fe73">copyAttributesFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a51d2023749f953a981e41484ca4ebfa6">llvm::GlobalAlias::create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#acc7ae6e57000b1f2e276fb96eba06213">llvm::GlobalAlias::create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#ab815632298cb8e2271e2a0e7062a7360">llvm::GlobalAlias::create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a311a097af4f0f77da22ac7acddc496f5">llvm::GlobalAlias::getAliaseeObject</a>, <a href="#a7017e24bb5f77030be934b76de3f58a4">getAliaseeObject</a>, <a href="#a788ede5201dc9b44e419e9fd2fbb38bf">getAliaseeObject</a>, <a href="#a6c3037bc9ccfd4637b88bc8281a4f889">getComdat</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a5b53de0b76d2880fb3e4b487cb4fee75">llvm::GlobalObject::GlobalObject</a>, <a href="#ac6beea678d6a163206b1ef36b1a59a02">GlobalValue</a> and <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a4b5d91825bd05a14280768680626e294">llvm::GlobalAlias::operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~GlobalValue() {#acbca9233f5cc59714d6bb6afe39ef9fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GlobalValue::~GlobalValue ()</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/constant/#a960620248182018e566b095f06a605df">llvm::Constant::removeDeadConstantUsers</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### canBenefitFromLocalAlias() {#aa63851a5f68b64cf93d3f8c4a973f33d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GlobalValue::canBenefitFromLocalAlias ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a43721e1e88567116e8fca545125d86bf">getComdat</a>, <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a>, <a href="#a3e6237ebf8cf834ae6fa726efccaef8d">hasDefaultVisibility</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a32e606ac4c88f71f14212e42b808e7f4">isDeclaration</a>, <a href="#a89a664b58385307fbb24c02e141d864b">isExternalLinkage</a>, <a href="#a40631ccf8ca06c1942f13f4872ed8e86">isTagged</a> and <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035ab2d0d4bc9ba11b7324f5ffc20a9dc37a">llvm::Comdat::NoDeduplicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a9a1560129bcae4e7e2456326461a8aa6">llvm::AsmPrinter::getSymbolPreferLocal</a>.</p>

</div>
</div>

### canBeOmittedFromSymbolTable() {#ae3a42354a5b89aa8ade55dab229036f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GlobalValue::canBeOmittedFromSymbolTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if GV can be left out of the object symbol table.</p>


<p>This is the case for linkonce_odr values whose address is not significant. While legal, it is not normally profitable to omit them from the .o symbol table. Using this analysis makes sense when the information can be passed down to the linker or we are in LTO.</p>


<p>Declaration at line 678 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#aaef9bedb9a16483f04717a57af933173">hasAtLeastLocalUnnamedAddr</a>, <a href="#ac18f876b955434599bd93fd50aad53b8">hasGlobalUnnamedAddr</a> and <a href="#ae28d149d03a6ae88267f649bc1dbe42c">hasLinkOnceODRLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a49170e37072dd286a1fcf76f2efec373">llvm::buildModuleSummaryIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#ae72ecc1f2bb5b8cf32d628a6cf5eeaba">canBeHidden</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>.</p>

</div>
</div>

### eraseFromParent() {#a7c733400ba8d113fd2976d4fea0db981}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalValue::eraseFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method unlinks 'this' from the containing module and deletes it.</p>

<p>Declaration at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#a4a6ca5a5b87bd84231be9d8dbec46c1a">llvm::Value::getValueID</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5a50ba4ab5027d4013cf6bc2edf66085">deleteIfDead</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a727a05f1cb9b333d251bd1485784d039">anonymous{ThinLTOBitcodeWriter.cpp}::promoteInternals</a>, <a href="/web-llvm/docs/api/classes/llvm/globaldcepass/#ae98558816f50b4a9f6f7244b2deadd53">llvm::GlobalDCEPass::run</a> and <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a0706966ac4f391854346bebfcda816fa">llvm::anonymous{AMDGPUSplitModule.cpp}::splitAMDGPUModule</a>.</p>

</div>
</div>

### getAbsoluteSymbolRange() {#a7918bda9a2e43bf56739cfe8c3d92803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ConstantRange &gt; GlobalValue::getAbsoluteSymbolRange ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is an absolute symbol reference, returns the range of the symbol, otherwise returns std::nullopt.</p>

<p>Declaration at line 647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5193c3535375c450b9430e5671cbeb2d">llvm::getConstantRangeFromMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#a9d5115303da1531a159c9527a549e6b5">llvm::X86Subtarget::classifyGlobalReference</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinefunction/#a6367c396ac6375707af64e0f9a8ad08f">llvm::AMDGPUMachineFunction::getLDSAbsoluteAddress</a>.</p>

</div>
</div>

### getAddressSpace() {#a702d4986803a1782ba305b1c7a0f1c21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValue::getAddressSpace ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8aeced5e71d2589fa3e9791043af5cb">llvm::PointerType::getAddressSpace</a> and <a href="#a913a5d4b2cddde762446bd494e81a3f2">getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucalllowering-cpp/#a0f19540db0c8b48eebad9481053dc719">addCallTargetOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinefunction/#a37239bfcbdcba6fbb3c2ca3226e2d90b">llvm::AMDGPUMachineFunction::allocateLDSGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e9604d679f4806943544dceaeb68149">llvm::convertToDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#acc7ae6e57000b1f2e276fb96eba06213">llvm::GlobalAlias::create</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a673ca077823c034cab2b172947847f19">llvm::AMDGPUAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a0202522d1384c2ad88417c496ae62068">llvm::WebAssemblyAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinefunction/#a6367c396ac6375707af64e0f9a8ad08f">llvm::AMDGPUMachineFunction::getLDSAbsoluteAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a1f130fccfd94dc59362cfcd4d1a4f6d8">llvm::VETargetLowering::getPICJumpTableRelocBase</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2c7b6b90ed9c390a20c7bb95dc2ec4d2">llvm::SelectionDAG::getSymbolFunctionGlobalAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuattributor-cpp/#a10dea573184b324cee05982745c07f27">isDSAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab3c030cff32b7d9d50fb47d37a1fcef6">llvm::AMDGPU::isGlobalSegment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a49897e4c6b2b01d68f4cc65cbb4e93e7">llvm::AMDGPU::isGroupSegment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5b6a1089ecf2f169db2202ce3340c17b">llvm::AMDGPU::isReadOnlySegment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a56b5a0fa4891dca73946affd4e6e3ffd">removeFromUsedList</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a88e01d7fa3f418c441946a2200eb12c0">llvm::SITargetLowering::shouldEmitFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a27bb49c3656188aff4e75ebc6d4147d5">llvm::SITargetLowering::shouldEmitGOTReloc</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#af376f4f0e0b55e40407912678b736863">SRAGlobal</a>.</p>

</div>
</div>

### getAliaseeObject() {#a788ede5201dc9b44e419e9fd2fbb38bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalObject * GlobalValue::getAliaseeObject ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp/#ade220311d6a189eb0902d703f4beef36">findBaseObject</a> and <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a15ad3b408efc55e12e201e1cd1dfbc45">anonymous{IRSymtab.cpp}::Builder::addSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#af5ca20f498adaec1f940475984ad7050">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::doInitialization</a>, <a href="#a43721e1e88567116e8fca545125d86bf">getComdat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/splitmodule-cpp/#ab3b6b24d035097cbcec613f6cc3c2bdd">getGVPartitioningRoot</a>, <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a2aa25f7f2b406e074ebced65fa3dd531">llvm::TargetLoweringObjectFileMachO::getNameWithPrefix</a>, <a href="#a7215706ede5f29b81e4f99af35e87aa6">getSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a21e02ce6503c32d68315d841724b9385">getSelectionForCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesymboltable/#a9c6d3dc79159798bdccacf3e0ee99468">llvm::ModuleSymbolTable::getSymbolFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">llvm::FunctionImporter::importFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ae5d09e961ee51900ce14d985bbc0839b">llvm::TargetMachine::isLargeGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ae601b00af8d8e80cd833ae31f78a9160">llvm::HexagonTargetLowering::LowerGLOBALADDRESS</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#a710c8f170506ce6c3abd66ada911e231">llvm::LanaiTargetLowering::LowerGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-linkmodules-cpp-/modulelinker/#a589fd28f47f98110e06d544523d59977">anonymous{LinkModules.cpp}::ModuleLinker::run</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>.</p>

</div>
</div>

### getAliaseeObject() {#a7017e24bb5f77030be934b76de3f58a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalObject * llvm::GlobalValue::getAliaseeObject ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a>.</p>

</div>
</div>

### getComdat() {#a43721e1e88567116e8fca545125d86bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Comdat * GlobalValue::getComdat ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a788ede5201dc9b44e419e9fd2fbb38bf">getAliaseeObject</a>, <a href="#a43721e1e88567116e8fca545125d86bf">getComdat</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#aa63851a5f68b64cf93d3f8c4a973f33d">canBenefitFromLocalAlias</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#ab80457ac1eada6ec15c0492e30e5d6e4">checkMachOComdat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5a50ba4ab5027d4013cf6bc2edf66085">deleteIfDead</a>, <a href="#a43721e1e88567116e8fca545125d86bf">getComdat</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a3a19103e69c6cb0ad95809d01b7b60cf">getComdatGVForCOFF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#ae2fad8392c4cfa8ead6bce638f70bbf5">getELFComdat</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a21e02ce6503c32d68315d841724b9385">getSelectionForCOFF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a8b7427173624577aaeb3201edcbd09b0">getWasmComdat</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#a4f0167f2ae072a399680c468a9777221">handleNonPrevailingComdat</a>, <a href="#aa9e5c8e6f11bf0df2b3e220bb6557418">hasComdat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/splitmodule-cpp/#a80f6063dd5f9d9d06818808cbb646f75">isInPartition</a>, <a href="/web-llvm/docs/api/classes/anonymous-linkmodules-cpp-/modulelinker/#a589fd28f47f98110e06d544523d59977">anonymous{LinkModules.cpp}::ModuleLinker::run</a> and <a href="/web-llvm/docs/api/classes/llvm/globaldcepass/#ae98558816f50b4a9f6f7244b2deadd53">llvm::GlobalDCEPass::run</a>.</p>

</div>
</div>

### getComdat() {#a6c3037bc9ccfd4637b88bc8281a4f889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Comdat * llvm::GlobalValue::getComdat ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a>.</p>

</div>
</div>

### getDataLayout() {#aa5d2c67dadc073dac78224224ee89350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout &amp; GlobalValue::getDataLayout ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the data layout of the module this global belongs to.</p>


<p>Requires the global to have a parent module.</p>


<p>Declaration at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/module/#abcbe492bce3ccc16e0bbb50292576c5c">llvm::Module::getDataLayout</a> and <a href="#a739b30c811f1eece61b05320ddf44e5b">getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa321836ddd72df66be5551323b3090d9">llvm::AsmPrinter::emitAlignment</a>, <a href="/web-llvm/docs/api/classes/anonymous-directxasmprinter-cpp-/dxilasmprinter/#a48b15639730822b6cab292e69f1a93a7">anonymous{DirectXAsmPrinter.cpp}::DXILAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a1592f31751bef2ac04349cb6be511d18">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a673ca077823c034cab2b172947847f19">llvm::AMDGPUAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a0202522d1384c2ad88417c496ae62068">llvm::WebAssemblyAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4b27e8ffe711b0dcbc16b19671d5edc">llvm::emitLinkerFlagsForGlobalCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4cc8d8a6afc7262b599109c2029fc311">llvm::AsmPrinter::emitSpecialLLVMGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#a667ed45ec1fd0b5557d48ac537ddad2d">getAlign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36b03d4697c30b32e8762cb0dfd66761">llvm::getConstantDataArrayInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#ade886f9a8ca0106ed64320647cbc1646">getELFSectionNameForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a3b63142ca24145028afa3a5bdf3fe7fb">llvm::ExecutionEngine::getMangledName</a>, <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a866133bf888d0b8bbce2275845511edb">llvm::TargetLoweringObjectFile::getSymbolWithGlobalValueBase</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#af9f31014b7b244d627f6bd18109c5987">llvm::GlobalVariable::GlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#aab3a49dcff02cbc78628deef02c53296">llvm::HexagonTargetObjectFile::isGlobalInSmallSection</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#a2adf1ff4e0a2e37ff5c9ebb3c68ea93e">llvm::RISCVELFTargetObjectFile::isGlobalInSmallSection</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a2f9fee96328939e708e6c2a26a10e49d">llvm::SystemZSubtarget::isPC32DBLSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ade4086b409f00a755cfc6c0b03f67413">isPointerValueDeadOnEntryToFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreisellowering-cpp/#a496a2f61ad3c4221c58805e32bc47e5c">IsSmallObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a40c243011cdda005e97448378d575096">performGlobalAddressCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3002d96da0f9030af718fbe2961b913f">llvm::ReadByteArrayFromGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#ac2b50ec3a5402b3063da7211a176f8ff">llvm::XCoreTargetObjectFile::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#afc576f8a8ddd42537a82e1cedc179ae1">tocDataChecks</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>.</p>

</div>
</div>

### getDLLStorageClass() {#af09a662b4e302d0683d0fe9dc2a9335f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DLLStorageClassTypes llvm::GlobalValue::getDLLStorageClass ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#af89f25d8a89068ab9be05f2a095da4ed">DllStorageClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#ae5c40040698f75dfff1fd6bb991c9ff8">getEncodedDLLStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilbitcodewriter/#a6ff87aa2d11681bf60bcbe10ef2f2ea4">llvm::dxil::DXILBitcodeWriter::getEncodedDLLStorageClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>.</p>

</div>
</div>

### getGlobalIdentifier() {#aed99d84162082a52cd08efb7dfe017e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string GlobalValue::getGlobalIdentifier ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the modified name for this global value suitable to be used as the key for a global lookup (e.g.</p>


<p>profile or ThinLTO).</p>


<p>Declaration at line 583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="#aed99d84162082a52cd08efb7dfe017e4">getGlobalIdentifier</a>, <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a> and <a href="#a739b30c811f1eece61b05320ddf44e5b">getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#a59c4cec2de3101c3788db6c4d84872dd">findValueInfoForFunc</a>, <a href="#aed99d84162082a52cd08efb7dfe017e4">getGlobalIdentifier</a>, <a href="#a71ee7e63264e4997a3340a781d44832e">getGUID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af25e9b73a31b54cd149a89a73b7032de">llvm::getIRPGONameForGlobalObject</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac69630533101ec5ba74953a63082148">llvm::thinLTOInternalizeModule</a>.</p>

</div>
</div>

### getGUID() {#a71ee7e63264e4997a3340a781d44832e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GUID llvm::GlobalValue::getGUID ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a 64-bit global unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> constructed from global value name (i.e.</p>


<p>returned by <a href="#aed99d84162082a52cd08efb7dfe017e4">getGlobalIdentifier()</a>).</p>


<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#aed99d84162082a52cd08efb7dfe017e4">getGlobalIdentifier</a> and <a href="#a71ee7e63264e4997a3340a781d44832e">getGUID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#ae52dc32e051ded6356e4065b75d19935">addIntrinsicToSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobehandler/#a852e00b0a303d6be050e6b6ee092c9b6">llvm::PseudoProbeHandler::emitPseudoProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/assignguidpass/#a00cd72af35cb6bdeae06467500b531ae">llvm::AssignGUIDPass::getGUID</a>, <a href="#a71ee7e63264e4997a3340a781d44832e">getGUID</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofrecord/#ace5015b378d124a205da5a1eaf98061e">llvm::memprof::IndexedMemProfRecord::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#a06ec58fca119b03f6ffea51610851571">llvm::ModuleSummaryIndex::getOrInsertTypeIdSummary</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-2f4f225abb34192a09a7e667de1c62d8/#a82f01bbe42ee34025935c92328063566">llvm::yaml::CustomMappingTraits&lt; TypeIdSummaryMapTy &gt;::inputOne</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileprober/#af77769bc44a5fe5006bbc89befd75e4b">llvm::SampleProfileProber::instrumentOneFunc</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#addf7542694401439f2f600b3890c8831">anonymous{WholeProgramDevirt.cpp}::DevirtModule::lookUpFunctionValueInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a51eeec9ea4e0b01342c3c5ded09d9d44">anonymous{AsmWriter.cpp}::AssemblyWriter::printModuleSummaryIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#ac7cd1bb8cb4a4e4e1ec44f5097cb071f">readMemprof</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtindex/#ad6378f806ed88c9d72ddcb04dacd75ce">anonymous{WholeProgramDevirt.cpp}::DevirtIndex::run</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a363028d7884038c73a4f3f2474530c33">anonymous{WholeProgramDevirt.cpp}::DevirtModule::run</a> and <a href="/web-llvm/docs/api/classes/llvm/lto/lto/#ada5eca1803d5afcb1005ea05ffc62636">llvm::lto::LTO::run</a>.</p>

</div>
</div>

### getLinkage() {#a3547d58a060ee2e4a29cbea85bef91af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkageTypes llvm::GlobalValue::getLinkage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>.</p>


<p>Referenced by <a href="#aa63851a5f68b64cf93d3f8c4a973f33d">canBenefitFromLocalAlias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aaa5acf165c5a3bec2ff360c59f2f9448">llvm::orc::cloneGlobalAliasDecl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a88db5656a6723001ab395e9db68094c2">llvm::orc::cloneGlobalVariableDecl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#a101d392f12933ec345c1cef1f552809e">copyLinkageVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a51d2023749f953a981e41484ca4ebfa6">llvm::GlobalAlias::create</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#ab7906bdf774a35b56cb2e908d012472c">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a78e5ec9027384598a0ce9fb4eb3cea72">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a83aca905c88deb0a7598e92f4f6558b0">llvm::AsmPrinter::emitLinkage</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#aa72747d7d3b33e66672520f5a3e93462">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitTTypeReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#aa88d9de56393e21d759a360f4b4948c0">getEncodedLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilbitcodewriter/#a586414510277aa6c4ef316c8644518a3">llvm::dxil::DXILBitcodeWriter::getEncodedLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#a97235ab99e26ebd8fe54f629666f6bd2">getFuncAddrForProfData</a>, <a href="#aed99d84162082a52cd08efb7dfe017e4">getGlobalIdentifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a975ec098acfb1abadef8f7e741bf5c5e">llvm::getIRPGOObjectName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a79b16b25c08c277de4d27f75a22f95e4">llvm::TargetLoweringObjectFileXCOFF::getStorageClassForGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a731bb8307207186d81b2a7353f21f199">getTOCEntryTypeForMO</a>, <a href="#ac90734e1bc3dc440f2db27f4c38a4f43">hasAppendingLinkage</a>, <a href="#ae76e0b39c563b63554b4c99a8ad726e4">hasAvailableExternallyLinkage</a>, <a href="#ac10ac4576e030b231e1fbb5a8272f01f">hasCommonLinkage</a>, <a href="#a1847e956a0087fefdb49e2a9583c7d18">hasExternalLinkage</a>, <a href="#a51af265dc931258cdb8ffb37ee6decee">hasExternalWeakLinkage</a>, <a href="#a7bc292fc6d075e3ed6e68b0866ec3524">hasInternalLinkage</a>, <a href="#a3acdc3a8bbb5f15edd761e8aee3e2dfd">hasLinkOnceAnyLinkage</a>, <a href="#a091e6599599c4e668373e0feefa92c01">hasLinkOnceLinkage</a>, <a href="#ae28d149d03a6ae88267f649bc1dbe42c">hasLinkOnceODRLinkage</a>, <a href="#a3ba1af4b9d9faa4a33729bbbecee83d1">hasLocalLinkage</a>, <a href="#a3ed4c5535997ad77ffee00f92430b576">hasPrivateLinkage</a>, <a href="#a334704e7c859bd7c44ca86249a6280cc">hasValidDeclarationLinkage</a>, <a href="#a61afb04130343acdd861174587400c10">hasWeakAnyLinkage</a>, <a href="#aaca0b3e9845b2fa35c965edaabd5c6bc">hasWeakLinkage</a>, <a href="#ab241086cb8a1e3f7e77fb00c9a8aeb2e">hasWeakODRLinkage</a>, <a href="#a863b49cf36a53aa979a81c6e10c4d6b5">isDiscardableIfUnused</a>, <a href="#aa1558e13ceef68db8ea9f4e3b5a64cbd">isInterposable</a>, <a href="#ac0495132fc83c026033c62c59b30489f">isWeakForLinker</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcorelowerthreadlocal-cpp-/xcorelowerthreadlocal/#adb1323a587666f6b6a98e4d7c2ba24af">anonymous{XCoreLowerThreadLocal.cpp}::XCoreLowerThreadLocal::lowerGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/extractgv-cpp/#aecd7db67c15393462f7d55af64644142">makeVisible</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a580ea5c66929553cd9bdc5741fbe2b1a">llvm::needsComdatForCounter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a6c0ba55113b40b07b869ba9c06db6ca1">OptimizeGlobalAliases</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a89d2a6c720f05584135f01f20cc3c9ee">anonymous{AsmWriter.cpp}::AssemblyWriter::printIFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae327be8503a76bd4dccfff4713a38553">llvm::OpenMPIRBuilder::registerTargetGlobalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#ac926ba61257c2262ebca3deca2cc8c76">replaceAliasWithAliasee</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a40b5636c9d406c277f51dcdcba06821f">anonymous{ExpandVariadics.cpp}::ExpandVariadics::runOnFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd3c2c7d03f515419a1785e0a2eb6ea8">llvm::setPGOFuncVisibility</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a9a13dab9647bddbb0cce81565a8249a1">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::uniquifyGVPerKernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95b7e7311ec52352ada27699c3c9c470">llvm::UpgradeGlobalVariable</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a2b81e19b3ddf7ec786c5105ba5470153">widenGlobalVariable</a>.</p>

</div>
</div>

### getParent() {#a739b30c811f1eece61b05320ddf44e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module * llvm::GlobalValue::getParent ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the module that this global value is contained inside of...</p>

<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#acb71c8012dfaa189618d2cdafb58b4b0">Parent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a0faf2520b671c3cb14b4f291c873cb88">addBoundsChecking</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a373d9e90c782cb9d8d84cbe4282f10d6">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::addPreEmitPass2</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-jmcinstrumenter-cpp-/#af680d052a24c294259bd765f02906202">anonymous{JMCInstrumenter.cpp}::attachDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroearly-cpp/#afbc0cbc36e72c326f3df01f017015786">buildDebugInfoForNoopResumeDestroyFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a881c9e75128e7e943b6d8f33606ccc74">llvm::SPIRVGlobalRegistry::buildGlobalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#a7227d9ecc33b8ed7a50b0d4341448c6c">calculateCXXStateNumbers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa75cdd420a3ce670e2c3b61046f2b8a7">llvm::calculateSEHStateNumbers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4547a0e8cb23afe1f8767916fd173920">llvm::calculateWinCXXEHStateNumbers</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ksubtarget/#a6e3c2fef3c61959152fccd82f06d3f59">llvm::M68kSubtarget::classifyGlobalFunctionReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#a74e467227d626db41ae5a4983a045508">llvm::X86Subtarget::classifyGlobalFunctionReference</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ksubtarget/#adcb8d02bb64a997fa76a9d566b9b2816">llvm::M68kSubtarget::classifyGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#a4882e7cf4e364e3201e76ab0fd425f6a">llvm::X86Subtarget::classifyGlobalReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac1b2be839460bb277d4f07f4aa5225ac">llvm::CloneFunctionInto</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a0e0ddbf81c5fa1ee764ba3f4bd6ddbf5">CompareValueComplexity</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a993771e7c58c60044cbc4c57f689406e">llvm::RandomIRBuilder::connectToSink</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#ae7de4da09df7011d92c1f4abd46134a2">llvm::MIRPrinter::convertMachineMetadataNodes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e9604d679f4806943544dceaeb68149">llvm::convertToDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#ab815632298cb8e2271e2a0e7062a7360">llvm::GlobalAlias::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a452dcc29fd5e19bda874218e10a8945c">createCloneDeclaration</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a8d1d93bb20bf72c7782cf68446e5bf9f">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::CreateFailCheckSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp/#a35929b5ae2c67d8c86640518636092ae">CreateGCStatepointCallCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp/#a2f89404be2430701edb3e9827aaab276">CreateGCStatepointInvokeCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a0202522d1384c2ad88417c496ae62068">llvm::WebAssemblyAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a8631130c37aa54ae6c9127abc5fe392a">llvm::AArch64TargetLowering::emitLoadLinked</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ab439771b84f342c37a8823fb2f797642">llvm::ARMTargetLowering::emitLoadLinked</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a683761fbb11ed0969edf7eee08b08bf3">llvm::PPCTargetLowering::emitMaskedAtomicCmpXchgIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a0e0d3c023e19c20fbf01b40d36aced80">llvm::PPCTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6245f16ff5b8230d2ed89127bf27efa8">llvm::AArch64TargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a68bc08431f00987920ce19e9a458e86d">llvm::ARMTargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#aaa3dfbded3ebc8068ad825a039bfdfaf">llvm::HexagonTargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a09b07d472515f1d307c0e8229f6856fb">llvm::GlobalAlias::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalifunc/#abd9f847c1058c8574d0c995f6c425fe8">llvm::GlobalIFunc::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#ae0cf03d5de37330b1eb69dd22a1d5057">llvm::GlobalVariable::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adfbecc9eaa3da520aafda5f3078baf3f">llvm::X86TargetLowering::expandIndirectJTBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9403490bd29139e7b814f7402cc3e87b">llvm::findAllNVVMAnnotation</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a537993928c8af5b0d064fcd5ce1dec2f">llvm::CodeExtractor::findAllocas</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac1dd7ea698f877f9b1aa11040f40f6d6">llvm::findOneNVVMAnnotation</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a8688fe7e12511bba710a19b4aaf027a1">llvm::RandomIRBuilder::findOrCreateSource</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp/#a682c8b1a578622031f16f4be7766b603">forceRenaming</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#aa66476422470ab204074b3198bcf4d15">llvm::JITSymbolFlags::fromGlobalValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a9cf59960e7146dd283b2f23753a00c3c">llvm::memtag::getAndroidSlotPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#afac5b39bcbb90d660f83d9b4bd8c6d95">llvm::CallBase::getCaller</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a3a19103e69c6cb0ad95809d01b7b60cf">getComdatGVForCOFF</a>, <a href="#aa5d2c67dadc073dac78224224ee89350">getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a5a8db261ae8a0e5359c65e8e8f8c1135">llvm::TargetLoweringBase::getDefaultSafeStackPointerLocation</a>, <a href="#aed99d84162082a52cd08efb7dfe017e4">getGlobalIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a784589f886057bdb03273b8bb07deb2b">llvm::TargetLoweringBase::getIRStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a4cb54e7d62530f9e973ff35f6301de6a">llvm::X86TargetLowering::getIRStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a7b91ad1b09dab040d3519c054e473efb">llvm::TargetLibraryInfoImpl::getLibFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a0f49cd7f0f28bd9b7aaed4b5a0df02d6">getLoadStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a2b4746e455f9041187249483e7f5e5f5">llvm::Loop::getLocStr</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a7f3d614408430191567752182cc78bf5">llvm::DbgRecord::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a0834f7a463c1bfa666cc9af2d8c80d8a">llvm::DbgRecord::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/trace/#af6a78a14ed8d5159ce626b046933b468">llvm::Trace::getModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a7b98dd2ff18a320795917ace7f8010db">getModuleFromDPI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#ad9b5eba01208d43c3c753251be70778a">llvm::memtag::getPC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1b127c37d77da045cea07e787e2d1e48">llvm::TargetLoweringBase::getSafeStackPointerLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2fd97f50411bc650c7f9f6e3118147f4">llvm::AMDGPULegalizerInfo::getSegmentAperture</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5f5de5d32f138fc104024357905735b">llvm::getStrippedSourceFileName</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2c7b6b90ed9c390a20c7bb95dc2ec4d2">llvm::SelectionDAG::getSymbolFunctionGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a9a1560129bcae4e7e2456326461a8aa6">llvm::AsmPrinter::getSymbolPreferLocal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#a8aa470cbd092a0baa198faf2e5174f94">GetSymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a07028bb765a646ca5ca5375162a93d7c">llvm::TargetMachine::getTLSModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a5640521ba3a9873a718e79f0bc49eadb">hasReturnsTwiceAttr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff719a7221f395b1b3849c9675ca32dd">llvm::inferAlignFromPtrInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ac5c4384a376959ec882f7650e427dbb5">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a12c711c62171c14dcedca2db5874d33e">llvm::SelectionDAGISel::initializeAnalysisResults</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#aafadfc35831cdb7ef3dd321cc28f1208">llvm::SelectionDAGISel::initializeAnalysisResults</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a69398364db52b18db9d922fec6d8eb87">llvm::MIRParserImpl::initializeConstantPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a1a4145a18b32a1bc1030bf789e370963">InsertCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp/#aaf5c6a95e57ae41b1bb74e87476d3dcc">insertCallBeforeInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a24da6451c0e494831c85fa96cb572c9a">insertSinCosCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a5ee07316c71711c956769e3dd902079e">isAtomicRMWLegalXChgTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4cacf18e8e9ecebd3f912ae0ad4e3817">llvm::AMDGPU::isDynamicLDS</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanabilist/#a643c870211a29b46598eb1630b61156a">anonymous{DataFlowSanitizer.cpp}::DFSanABIList::isIn</a>, <a href="#aa1558e13ceef68db8ea9f4e3b5a64cbd">isInterposable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af9de933caeeaebd4387c7c62f02a3bbd">llvm::AMDGPULegalizerInfo::legalizeTrapHsaQueuePtr</a>, <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalvariable/#ga3d3196c1f51231e2639321265f2f9ba9">LLVMGetNextGlobal</a>, <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalalias/#ga4b794045d4797dcb9ce36dac26e18341">LLVMGetNextGlobalAlias</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueglobalifunc/#ga26f3e0f1fb15709537936476b44da768">LLVMGetNextGlobalIFunc</a>, <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalvariable/#ga658b44552d64b26c308bce8b4ffa02d6">LLVMGetPreviousGlobal</a>, <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalalias/#gab53f2ccab1363e10116a064467c4837d">LLVMGetPreviousGlobalAlias</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueglobalifunc/#gae19214b102baae71f805de3544b30247">LLVMGetPreviousGlobalIFunc</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcorelowerthreadlocal-cpp-/xcorelowerthreadlocal/#adb1323a587666f6b6a98e4d7c2ba24af">anonymous{XCoreLowerThreadLocal.cpp}::XCoreLowerThreadLocal::lowerGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a8c1423d81607a5548a57bf11a3ab447c">llvm::SparcTargetLowering::makeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aa7fcaa7855f4688864e1315a38ab3694">llvm::X86TargetLowering::markLibCallAttributes</a>, <a href="#ac1b5643f40dd3c7b92a548027eb13de0">materialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/classes/llvm/insertfunctionstrategy/#a51a23cfe8db3e31fdc6eeb8547df0d33">llvm::InsertFunctionStrategy::mutate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#ad9f5610f1837c8d9df4a404f2b880b63">parseGlobalValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a21ef92ee94136c11407030eee4319eab">parseIRConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#afa9b4a650e1a6de2061538a19be3a234">llvm::MemorySSA::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a89d2a6c720f05584135f01f20cc3c9ee">anonymous{AsmWriter.cpp}::AssemblyWriter::printIFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#af20e7dedda7fbf6fc831745308eddeb9">printMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#ab31b894cd23f1d93468a50153a385fa1">llvm::memtag::readRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#aa4afd53102b414c23761c32f33b6cd08">llvm::GlobalAlias::removeFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalifunc/#a5892574848285e3ff045d123520a165a">llvm::GlobalIFunc::removeFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a22e076c4cf000eba885dd00048641c6f">llvm::GlobalVariable::removeFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08f3f942afc0ee9115a8f9fa87e9191d">llvm::RemoveRedundantDbgInstrs</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfopropagate-cpp-/regusageinfopropagation/#a69819f2acbe4f8a2cd38c871d3c9b96f">anonymous{RegUsageInfoPropagate.cpp}::RegUsageInfoPropagation::run</a>, <a href="/web-llvm/docs/api/classes/llvm/livestacksprinterpass/#aa3bb974f54082b4cda61faff8b9756c0">llvm::LiveStacksPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/printmirpass/#a354177020e92f5ab2dd0433a47123270">llvm::PrintMIRPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regusageinfocollectorpass/#a387db9c3806e18b7691b075381d0ac09">llvm::RegUsageInfoCollectorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regusageinfopropagationpass/#ab365c22ad0becb1f9a4f0fc2d85f088f">llvm::RegUsageInfoPropagationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicatepassbase/#a0780ac5d6a2962adf46e1c611e6ca6fa">llvm::TailDuplicatePassBase&lt; DerivedT, PreRegAlloc &gt;::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a53fcf95621b95aa7165074a98b5df0b3">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/stackprotector/#ad6088af9690051701647680fd467ed97">llvm::StackProtector::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguardlongjmp-cpp-/cfguardlongjmp/#a17b3d486f52582c92dec4b050aedb70a">anonymous{CFGuardLongjmp.cpp}::CFGuardLongjmp::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ehcontguardcatchret-cpp-/ehcontguardcatchret/#a6340bc98382b1dce1a1e8648fd72732b">anonymous{EHContGuardCatchret.cpp}::EHContGuardCatchret::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-kcfi-cpp-/kcfi/#a52015a7e0851334318eafd219c0412ba">anonymous{KCFI.cpp}::KCFI::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-pseudoprobeinserter-cpp-/pseudoprobeinserter/#acf62b36239ac36c52ffc9a58a18332ab">anonymous{PseudoProbeInserter.cpp}::PseudoProbeInserter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86indirectbranchtracking-cpp-/x86indirectbranchtrackingpass/#a0c58ed329a5ca544b28635282c0373df">anonymous{X86IndirectBranchTracking.cpp}::X86IndirectBranchTrackingPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86returnthunks-cpp-/x86returnthunks/#ab4a10d58e295ec66ff8c9c1d3eeb0529">anonymous{X86ReturnThunks.cpp}::X86ReturnThunks::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a72a62fe526ad0cd3c24cfe003d363df0">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-xrayinstrumentation-cpp-/xrayinstrumentation/#a4fb91ea8621a93ca73b483592ac6b061">anonymous{XRayInstrumentation.cpp}::XRayInstrumentation::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuresourceusageanalysis/#abc3887b23032d20ff538f82f3e5f4867">llvm::AMDGPUResourceUsageAnalysis::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a1ad010e488dcef9a629eb57ccd67d32d">selectExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf2ff3020b311fe77e208f80459017aa">llvm::setGlobalVariableLargeSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#a0062c60d49f66bddf4bc7fc76ce2968f">shouldRecordVTableAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#af376f4f0e0b55e40407912678b736863">SRAGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6a3e2feaa7c55f28c3095ef8a747ae7d">transformCallee</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3219f7b717320ae52f53ccb09ad5a84">llvm::tryPromoteCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aadfa6a6899cb32e0b249dfe7d5ab904b">UseTlsOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae8662f747218aee8ddeb4cdfbd1435a7">llvm::SelectionDAGBuilder::visitSPDescriptorParent</a>.</p>

</div>
</div>

### getParent() {#a0a3012859837d61e5de0037879333749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module * llvm::GlobalValue::getParent ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#acb71c8012dfaa189618d2cdafb58b4b0">Parent</a>.</p>

</div>
</div>

### getPartition() {#a72237a63b5edcf78a32453822139f1d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef GlobalValue::getPartition ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a016dccd2194d0bcf0c171921ac089569">llvm::LLVMContextImpl::GlobalValuePartitions</a>, <a href="#a0bf930687efa9a6cdc47d318dbd2e6d4">hasPartition</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aa142c8c536b95dd8e8a243cb67b57a80">llvm::LLVMContext::pImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a89d2a6c720f05584135f01f20cc3c9ee">anonymous{AsmWriter.cpp}::AssemblyWriter::printIFunc</a>.</p>

</div>
</div>

### getSanitizerMetadata() {#a10dbf1e2be9c60af49efb9bfded99225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SanitizerMetadata &amp; GlobalValue::getSanitizerMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a0870bd38114456f0b723d2a5dc741879">llvm::LLVMContextImpl::GlobalValueSanitizerMetadata</a>, <a href="#a6d863ff0d778248ac9b693db3494565c">hasSanitizerMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aa142c8c536b95dd8e8a243cb67b57a80">llvm::LLVMContext::pImpl</a>.</p>


<p>Referenced by <a href="#a40631ccf8ca06c1942f13f4872ed8e86">isTagged</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>.</p>

</div>
</div>

### getSection() {#a7215706ede5f29b81e4f99af35e87aa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef GlobalValue::getSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#a788ede5201dc9b44e419e9fd2fbb38bf">getAliaseeObject</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a43a17d867ea4d3bca00dfb065f8cc811">callsShareTOCBase</a> and <a href="#a9f52d196211845d0d605733e2f699055">hasSection</a>.</p>

</div>
</div>

### getThreadLocalMode() {#a52126ae2091b18cecfd5ad0f0012839a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadLocalMode llvm::GlobalValue::getThreadLocalMode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#acf0096839ddf4913784dfaa716329064">ThreadLocal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a88db5656a6723001ab395e9db68094c2">llvm::orc::cloneGlobalVariableDecl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e9604d679f4806943544dceaeb68149">llvm::convertToDeclaration</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a78e5ec9027384598a0ce9fb4eb3cea72">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a63d62b881d3a85b6b75b5c8153c8f693">getEncodedThreadLocalMode</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilbitcodewriter/#a27deb340295be3eb8c6fa8b611944e6f">llvm::dxil::DXILBitcodeWriter::getEncodedThreadLocalMode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a2ddf5387f9cd603891e1933c2f84cf65">llvm::TargetLoweringObjectFileXCOFF::getSectionForExternalReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachine-cpp/#a42137744a6ac05132bc99060fae4a0e3">getSelectedTLSModel</a>, <a href="#a239427c2c3a01e23bd15b29633696536">isThreadLocal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a56b5a0fa4891dca73946affd4e6e3ffd">removeFromUsedList</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#af376f4f0e0b55e40407912678b736863">SRAGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a9a13dab9647bddbb0cce81565a8249a1">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::uniquifyGVPerKernel</a>.</p>

</div>
</div>

### getType() {#a913a5d4b2cddde762446bd494e81a3f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType * llvm::GlobalValue::getType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Global values are always pointers.</p>

<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a0ac2ceaa32ba0511bb9e14e6edfbc329">llvm::MachineIRBuilder::buildGlobalValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#ae277c85704c17a21f772da0aee54fbaa">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::buildNonKernelLDSBaseTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxasmprinter-cpp/#af8ddf23c91f9cc1ae1e1d4ff1a133259">canDemoteGlobalVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/directxirpasses/pointertypeanalysis-cpp/#ac6745cfa7af2beebe88a7d3609c7875d">classifyGlobalCtorPointerType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aaa5acf165c5a3bec2ff360c59f2f9448">llvm::orc::cloneGlobalAliasDecl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a88db5656a6723001ab395e9db68094c2">llvm::orc::cloneGlobalVariableDecl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e9604d679f4806943544dceaeb68149">llvm::convertToDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a7db9daa323dee69eb9ecc380ce6edae8">llvm::OpenMPIRBuilder::createTargetInit</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode/#a92c5f6f2c447c5979d74ac07b552ba1e">llvm::GlobalAddressSDNode::getAddressSpace</a>, <a href="#a702d4986803a1782ba305b1c7a0f1c21">getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7ee632093c5fc25ca22faa353105aa74">llvm::SelectionDAG::getGlobalAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a071c6530f4d3362b846fdc1701c216e9">getTLIFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8d72d0dbb6d5ab8b970a32519122d85c">llvm::SelectionDAG::InferPtrAlign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e3103683ccd8b97050f821110b98ad2">llvm::IsConstantOffsetFromGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4cacf18e8e9ecebd3f912ae0ad4e3817">llvm::AMDGPU::isDynamicLDS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad96e48bda36fb8540a3973cee993c5b3">isKnownNonZeroFromAssume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a9a6f055381f5a946e37ab4d9e4a221d8">llvm::AMDGPU::isLDSVariableToLower</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#a6ebdfd799686fe407798a4d503a41cd9">isUnmergeableGlobal</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a273e9b97fc0dfec8df7cf4294d9b87fe">llvm::Attributor::isValidFunctionSignatureRewrite</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcorelowerthreadlocal-cpp-/xcorelowerthreadlocal/#adb1323a587666f6b6a98e4d7c2ba24af">anonymous{XCoreLowerThreadLocal.cpp}::XCoreLowerThreadLocal::lowerGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a89d2a6c720f05584135f01f20cc3c9ee">anonymous{AsmWriter.cpp}::AssemblyWriter::printIFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a07714583aa2bea29cd0284d5340dd844">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::replaceUseWithTableLookup</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmergeimpl/#a9fbe2dcb11cb3bb78be4d97f388b0c5d">anonymous{GlobalMerge.cpp}::GlobalMergeImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxgenerictonvvm-cpp-/generictonvvm/#ad0fae911d15e72e7f72b040a655dc081">anonymous{NVPTXGenericToNVVM.cpp}::GenericToNVVM::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a629a9b41f0b6dfa91f5b0a7ac34f2d1a">llvm::GlobalAlias::setAliasee</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a9a13dab9647bddbb0cce81565a8249a1">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::uniquifyGVPerKernel</a>.</p>

</div>
</div>

### getUnnamedAddr() {#ac2417a3c6edd0db7a9ad84b82c4054b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnnamedAddr llvm::GlobalValue::getUnnamedAddr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#af8c3ae3e5e774d859ca9b52521a537af">UnnamedAddrVal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a7fb389ba93facff2787add2c58128fcb">getEncodedUnnamedAddr</a>, <a href="#aaef9bedb9a16483f04717a57af933173">hasAtLeastLocalUnnamedAddr</a>, <a href="#ac18f876b955434599bd93fd50aad53b8">hasGlobalUnnamedAddr</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5cb8771722bfd8bcbdeb391b17e6cfd6">processGlobal</a>.</p>

</div>
</div>

### getValueType() {#af1dd2acfc2950742e41a64a342b15c80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::GlobalValue::getValueType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#a177d1baba701de456c801ac1c05979b9">ValueType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#aeddd04f458fd6e9db5a892543636e240">addEmuTlsVar</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinefunction/#a37239bfcbdcba6fbb3c2ca3226e2d90b">llvm::AMDGPUMachineFunction::allocateLDSGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a6d4194ac737935234600bb19108a8042">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::chooseBestVariableForModuleStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a61b99558b55ac0e86169e5b7eb6ad193">llvm::AArch64Subtarget::classifyGlobalFunctionReference</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#aa2bf24e995494a7c64d8f3e02818ad30">llvm::AArch64Subtarget::ClassifyGlobalReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aaa5acf165c5a3bec2ff360c59f2f9448">llvm::orc::cloneGlobalAliasDecl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a88db5656a6723001ab395e9db68094c2">llvm::orc::cloneGlobalVariableDecl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e9604d679f4806943544dceaeb68149">llvm::convertToDeclaration</a>, <a href="/web-llvm/docs/api/classes/anonymous-executionengine-cpp-/gvmemoryblock/#a2cbb49e0b488e91387da02f0396405f7">anonymous{ExecutionEngine.cpp}::GVMemoryBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#acc7ae6e57000b1f2e276fb96eba06213">llvm::GlobalAlias::create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8240180b602f60980be558e3cd44b460">llvm::IRBuilderBase::CreateGlobalStringPtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#a082d0b0afa7b05bf751feabbc3550f2b">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::emitArrayBound</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a2773eb6f0be68426806ef8f68bdd4393">llvm::AsmPrinter::emitGlobalAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a673ca077823c034cab2b172947847f19">llvm::AMDGPUAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#ab98a836a506bb90245c243f8e4da3162">llvm::ExecutionEngine::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a0202522d1384c2ad88417c496ae62068">llvm::WebAssemblyAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4b27e8ffe711b0dcbc16b19671d5edc">llvm::emitLinkerFlagsForGlobalCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a8d9ad0ef3d9122df6d6b4007c519c61e">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getAddressesOfVariablesInKernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aaf7c3ea495e589d05c4e89f7c9dcc897">llvm::AMDGPU::getAlign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36b03d4697c30b32e8762cb0dfd66761">llvm::getConstantDataArrayInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#abc7937248226859bf5a5d64a28c8269f">llvm::DataLayout::getPreferredAlign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4cacf18e8e9ecebd3f912ae0ad4e3817">llvm::AMDGPU::isDynamicLDS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af1ef95140ed897d441343e4a93d37726">isFunctionGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#aab3a49dcff02cbc78628deef02c53296">llvm::HexagonTargetObjectFile::isGlobalInSmallSection</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#a2adf1ff4e0a2e37ff5c9ebb3c68ea93e">llvm::RISCVELFTargetObjectFile::isGlobalInSmallSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanabilist/#a643c870211a29b46598eb1630b61156a">anonymous{DataFlowSanitizer.cpp}::DFSanABIList::isIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ace2885fc42e68606f270bfd3180d5f26">isLeakCheckerRoot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a98625eaa7fa561edb6921fc5c7fcefcd">llvm::AMDGPU::isNamedBarrier</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a2f9fee96328939e708e6c2a26a10e49d">llvm::SystemZSubtarget::isPC32DBLSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreisellowering-cpp/#a496a2f61ad3c4221c58805e32bc47e5c">IsSmallObject</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a04975f118b224e8cd322d1aa86f2ceb2">llvm::AMDGPULegalizerInfo::legalizeGlobalValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcorelowerthreadlocal-cpp-/xcorelowerthreadlocal/#adb1323a587666f6b6a98e4d7c2ba24af">anonymous{XCoreLowerThreadLocal.cpp}::XCoreLowerThreadLocal::lowerGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a2f68fd99d1f5c6c8326be57c2963306d">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::lowerKernelLDSAccesses</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#aa50d150829937efa73527accf23a184d">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerLOADgotAUTH</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a22c90a0d582e484ad655a9f337002b05">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerMOVaddrPAC</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a11f3804d12832cad99941719e39a960d">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::lowerNonKernelLDSAccesses</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#a58e10a8e8f7c27c724cd88a29f2739e5">anonymous{AMDGPUSwLowerLDS.cpp}::markUsedByKernel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ad7593156486a0b9a2c48cfd1ab7b29a5">parseJumpTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a40c243011cdda005e97448378d575096">performGlobalAddressCombine</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a7bc472aa7f200453c2fb1d5fbc404b66">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::populateSwMetadataGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a89d2a6c720f05584135f01f20cc3c9ee">anonymous{AsmWriter.cpp}::AssemblyWriter::printIFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae327be8503a76bd4dccfff4713a38553">llvm::OpenMPIRBuilder::registerTargetGlobalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a56b5a0fa4891dca73946affd4e6e3ffd">removeFromUsedList</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a547d3856bc525978c9c94694b2f8cb20">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::replaceKernelLDSAccesses</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmergeimpl/#a9fbe2dcb11cb3bb78be4d97f388b0c5d">anonymous{GlobalMerge.cpp}::GlobalMergeImpl::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#ad30c8bb172d913f5fb4a3d850bb7a4d2">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#ac2b50ec3a5402b3063da7211a176f8ff">llvm::XCoreTargetObjectFile::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinefunction/#a525be06bfa09ba3686ce7a9406a3f6cf">llvm::AMDGPUMachineFunction::setDynLDSAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a095f8f031d99ce3c0b25478713293dea">llvm::GlobalVariable::setInitializer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a004b3a18ad13375ad40e88cd41a0fe97">shouldConvertToRelLookupTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a27bb49c3656188aff4e75ebc6d4147d5">llvm::SITargetLowering::shouldEmitGOTReloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#af376f4f0e0b55e40407912678b736863">SRAGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#afc576f8a8ddd42537a82e1cedc179ae1">tocDataChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#a74dbf3215dd56f387425123cbff44a36">llvm::SCCPInstVisitor::trackValueOfGlobalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a44ca78ca7013578c50cdd38647811346">transformGlobalArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a9a13dab9647bddbb0cce81565a8249a1">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::uniquifyGVPerKernel</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#aae5f020a66b7a61f16cf63e17fa31e56">anonymous{StructuralHash.cpp}::StructuralHashImpl::update</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a7706251a7f258b126499e2f50f9348b5">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::updateMallocSizeForDynamicLDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95b7e7311ec52352ada27699c3c9c470">llvm::UpgradeGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a32bd3fc6040488f54b8fb322216218a5">DataScalarizerVisitor::visitGetElementPtrInst</a> and <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a29d90faf3dd7128f83eca30377481bfe">llvm::ObjectSizeOffsetVisitor::visitGlobalVariable</a>.</p>

</div>
</div>

### getVisibility() {#a28b9561d9ef3d237ef894023187fa26c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VisibilityTypes llvm::GlobalValue::getVisibility ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#a4b20bb41f6274a04399a83a821869ad1">Visibility</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#a101d392f12933ec345c1cef1f552809e">copyLinkageVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a2773eb6f0be68426806ef8f68bdd4393">llvm::AsmPrinter::emitGlobalAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a673ca077823c034cab2b172947847f19">llvm::AMDGPUAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a0202522d1384c2ad88417c496ae62068">llvm::WebAssemblyAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a78e5ec9027384598a0ce9fb4eb3cea72">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a3a7e88942eb67dbe7eb580dbdf75c648">getEncodedVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilbitcodewriter/#a82c3d62e3e31689738ff29dc4c2bceb5">llvm::dxil::DXILBitcodeWriter::getEncodedVisibility</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a89d2a6c720f05584135f01f20cc3c9ee">anonymous{AsmWriter.cpp}::AssemblyWriter::printIFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#ac926ba61257c2262ebca3deca2cc8c76">replaceAliasWithAliasee</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a40b5636c9d406c277f51dcdcba06821f">anonymous{ExpandVariadics.cpp}::ExpandVariadics::runOnFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#ab56b58aa044c07dc0bea0c0662c9d2ae">shouldUsePublicSymbol</a>.</p>

</div>
</div>

### hasAppendingLinkage() {#ac90734e1bc3dc440f2db27f4c38a4f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasAppendingLinkage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#a0b09f704d0928e6811660fa3af8f626c">isAppendingLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4cc8d8a6afc7262b599109c2029fc311">llvm::AsmPrinter::emitSpecialLLVMGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a37e41a7f6870d875dafe144485f2fb3f">isSpecialLLVMGlobalArrayToSkip</a> and <a href="/web-llvm/docs/api/classes/anonymous-irmover-cpp-/irlinker/#a29e247c718172acd518f8bb0255ff851">anonymous{IRMover.cpp}::IRLinker::run</a>.</p>

</div>
</div>

### hasAtLeastLocalUnnamedAddr() {#aaef9bedb9a16483f04717a57af933173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasAtLeastLocalUnnamedAddr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this value's address is not significant in this module.</p>


<p>This attribute is intended to be used only by the code generator and LTO to allow the linker to decide whether the global needs to be in the symbol table. It should probably not be used in optimizations, as the value may have uses outside the module; use <a href="#ac18f876b955434599bd93fd50aad53b8">hasGlobalUnnamedAddr()</a> instead.</p>


<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#ac2417a3c6edd0db7a9ad84b82c4054b7">getUnnamedAddr</a> and <a href="#ae8df4be75bfc50b1eadd74e85c25fa45a6adf97f83acf6453d4a6a4b1070f3754">None</a>.</p>


<p>Referenced by <a href="#ae3a42354a5b89aa8ade55dab229036f6">canBeOmittedFromSymbolTable</a>.</p>

</div>
</div>

### hasAvailableExternallyLinkage() {#ae76e0b39c563b63554b4c99a8ad726e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasAvailableExternallyLinkage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#a578061260691a59a9e7b0455fd68359c">isAvailableExternallyLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4cc8d8a6afc7262b599109c2029fc311">llvm::AsmPrinter::emitSpecialLLVMGlobal</a>, <a href="#a6b66f492cbea5f4b4f434d7178477116">isDeclarationForLinker</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetobjectfile/#aa748aed9bae156d6952b2695928bafc4">llvm::MipsTargetObjectFile::IsGlobalInSmallSection</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetobjectfile/#abf75c3694d93018762e04b063152b4ba">llvm::LanaiTargetObjectFile::isGlobalInSmallSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#a0062c60d49f66bddf4bc7fc76ce2968f">shouldRecordVTableAddr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>.</p>

</div>
</div>

### hasComdat() {#aa9e5c8e6f11bf0df2b3e220bb6557418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasComdat ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#a43721e1e88567116e8fca545125d86bf">getComdat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a43a17d867ea4d3bca00dfb065f8cc811">callsShareTOCBase</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a83aca905c88deb0a7598e92f4f6558b0">llvm::AsmPrinter::emitLinkage</a>.</p>

</div>
</div>

### hasCommonLinkage() {#ac10ac4576e030b231e1fbb5a8272f01f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasCommonLinkage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#a76d750f65089b2e70a927cf9d275a9d7">isCommonLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#abfc9f5d963c447cbe28355bc7887d1bd">llvm::X86Subtarget::classifyLocalReference</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#af5ca20f498adaec1f940475984ad7050">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#a082d0b0afa7b05bf751feabbc3550f2b">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::emitArrayBound</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#ab7906bdf774a35b56cb2e908d012472c">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#aa66476422470ab204074b3198bcf4d15">llvm::JITSymbolFlags::fromGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#acf4019263b41c295bc55032dd651b6e4">llvm::HexagonTargetObjectFile::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#a2adf1ff4e0a2e37ff5c9ebb3c68ea93e">llvm::RISCVELFTargetObjectFile::isGlobalInSmallSection</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a43deb1b2c2e73ff4adac8e70e91b672b">llvm::ARMSubtarget::isGVIndirectSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#ab64771f762bdb53411b08c38f9d7b125">llvm::HexagonTargetObjectFile::SelectSectionForGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#afa6dda813be79bdc7753ef52b9b5ec56">llvm::TargetLoweringObjectFileXCOFF::SelectSectionForGlobal</a>.</p>

</div>
</div>

### hasDefaultVisibility() {#a3e6237ebf8cf834ae6fa726efccaef8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasDefaultVisibility ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a9141f967188383108a69cc1b8ed3c195a2491e41d821f1d8fd3958ce3df2fddb2">DefaultVisibility</a> and <a href="#a4b20bb41f6274a04399a83a821869ad1">Visibility</a>.</p>


<p>Referenced by <a href="#aa63851a5f68b64cf93d3f8c4a973f33d">canBenefitFromLocalAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a78e5ec9027384598a0ce9fb4eb3cea72">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ab084a1deda97f9a90c7c8074c4e6ac6f">inferDSOLocal</a> and <a href="#a2df2f2e94b5493e9434dbf1c483dbc72">isImplicitDSOLocal</a>.</p>

</div>
</div>

### hasDLLExportStorageClass() {#a6a94ead7cfc2b5b3c035be6fe7b52a4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasDLLExportStorageClass ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a6948096330886cc831391c75adbadaf8a81819441fb6de420d4290ac79aaf9dc0">DLLExportStorageClass</a> and <a href="#af89f25d8a89068ab9be05f2a095da4ed">DllStorageClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a78e5ec9027384598a0ce9fb4eb3cea72">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitLinkage</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac4b27e8ffe711b0dcbc16b19671d5edc">llvm::emitLinkerFlagsForGlobalCOFF</a>.</p>

</div>
</div>

### hasDLLImportStorageClass() {#a66501d6d43642a526ab769458d700aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasDLLImportStorageClass ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a6948096330886cc831391c75adbadaf8aadc8e43e72669932581b5243b4b444b6">DLLImportStorageClass</a> and <a href="#af89f25d8a89068ab9be05f2a095da4ed">DllStorageClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a61b99558b55ac0e86169e5b7eb6ad193">llvm::AArch64Subtarget::classifyGlobalFunctionReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#afa6cb69d74a302b1314319c28d9435ec">llvm::X86Subtarget::classifyGlobalFunctionReference</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#aa2bf24e995494a7c64d8f3e02818ad30">llvm::AArch64Subtarget::ClassifyGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#a9d5115303da1531a159c9527a549e6b5">llvm::X86Subtarget::classifyGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a83de3f9ab24662688a50952de742a4dd">llvm::ARMBaseInstrInfo::expandLoadStackGuardBase</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#aa5423d2fba2a995d71e3294b14a19bbc">isFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#aa3f0dc829be1fe9aa1c7d5151db1bf21">llvm::TargetMachine::shouldAssumeDSOLocal</a>.</p>

</div>
</div>

### hasExactDefinition() {#a52355f8a15cd7cedfe83bd82b59e942a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasExactDefinition ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this global has an exact defintion.</p>

<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a32e606ac4c88f71f14212e42b808e7f4">isDeclaration</a> and <a href="#a008adb117253c7a0dde2f796be489d65">isDefinitionExact</a>.</p>

</div>
</div>

### hasExternalLinkage() {#a1847e956a0087fefdb49e2a9583c7d18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasExternalLinkage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#a89a664b58385307fbb24c02e141d864b">isExternalLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a61b99558b55ac0e86169e5b7eb6ad193">llvm::AArch64Subtarget::classifyGlobalFunctionReference</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#a082d0b0afa7b05bf751feabbc3550f2b">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::emitArrayBound</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a2773eb6f0be68426806ef8f68bdd4393">llvm::AsmPrinter::emitGlobalAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#aca88a09e03611e624c1b6ac0aad41ce3">llvm::ExecutionEngine::emitGlobals</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#ae36c2a9293b9a50a2870d02f93d7d202">llvm::RecordStreamer::flushSymverDirectives</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#acf4019263b41c295bc55032dd651b6e4">llvm::HexagonTargetObjectFile::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8476d36f91161750b845b56f25cb7c47">llvm::AArch64MCInstLower::GetGlobalValueSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#a2adf1ff4e0a2e37ff5c9ebb3c68ea93e">llvm::RISCVELFTargetObjectFile::isGlobalInSmallSection</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a04975f118b224e8cd322d1aa86f2ceb2">llvm::AMDGPULegalizerInfo::legalizeGlobalValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmergeimpl/#a9fbe2dcb11cb3bb78be4d97f388b0c5d">anonymous{GlobalMerge.cpp}::GlobalMergeImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#accbe3daa3b618020c7f900a4ca110f91">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#ab64771f762bdb53411b08c38f9d7b125">llvm::HexagonTargetObjectFile::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ab870ac74feb45bb48a75027da41c0784">llvm::SITargetLowering::shouldUseLDSConstAddress</a>.</p>

</div>
</div>

### hasExternalWeakLinkage() {#a51af265dc931258cdb8ffb37ee6decee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasExternalWeakLinkage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#a25e8e3490a28e9178b302b76ae643443">isExternalWeakLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#aa2bf24e995494a7c64d8f3e02818ad30">llvm::AArch64Subtarget::ClassifyGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#aca88a09e03611e624c1b6ac0aad41ce3">llvm::ExecutionEngine::emitGlobals</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ab084a1deda97f9a90c7c8074c4e6ac6f">inferDSOLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#aba8fa9d02ad8b557faaf41b37b714ba4">llvm::AArch64CallLowering::isEligibleForTailCallOptimization</a>, <a href="#a2df2f2e94b5493e9434dbf1c483dbc72">isImplicitDSOLocal</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#aa50d150829937efa73527accf23a184d">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerLOADgotAUTH</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#aa3f0dc829be1fe9aa1c7d5151db1bf21">llvm::TargetMachine::shouldAssumeDSOLocal</a> and <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a29d90faf3dd7128f83eca30377481bfe">llvm::ObjectSizeOffsetVisitor::visitGlobalVariable</a>.</p>

</div>
</div>

### hasGlobalUnnamedAddr() {#ac18f876b955434599bd93fd50aad53b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasGlobalUnnamedAddr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#ac2417a3c6edd0db7a9ad84b82c4054b7">getUnnamedAddr</a> and <a href="#ae8df4be75bfc50b1eadd74e85c25fa45a4cc6684df7b4a92b1dec6fce3264fac8">Global</a>.</p>


<p>Referenced by <a href="#ae3a42354a5b89aa8ade55dab229036f6">canBeOmittedFromSymbolTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a1db077f1815950aa2f419be901c429c6">isGOTEquivalentCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#aea4ff3e43adee428c84e0894ea75028a">makeMergeable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5cb8771722bfd8bcbdeb391b17e6cfd6">processGlobal</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4f18aa17f81c88c8fa89c76563a6d510">tryWidenGlobalArraysUsedByMemcpy</a>.</p>

</div>
</div>

### hasHiddenVisibility() {#a50baaf8d8a18c0cda69eb8d8eca178f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasHiddenVisibility ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a9141f967188383108a69cc1b8ed3c195a7eade123587a08e674f2ca72e2443771">HiddenVisibility</a> and <a href="#a4b20bb41f6274a04399a83a821869ad1">Visibility</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac4b27e8ffe711b0dcbc16b19671d5edc">llvm::emitLinkerFlagsForGlobalCOFF</a> and <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#aa66476422470ab204074b3198bcf4d15">llvm::JITSymbolFlags::fromGlobalValue</a>.</p>

</div>
</div>

### hasInternalLinkage() {#a7bc292fc6d075e3ed6e68b0866ec3524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasInternalLinkage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#a9bbb20d12147495c229051feded37cdc">isInternalLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a61b99558b55ac0e86169e5b7eb6ad193">llvm::AArch64Subtarget::classifyGlobalFunctionReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac9d0f2b6d9ec3c966243a29f8c8c7494">getADAEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#acf4019263b41c295bc55032dd651b6e4">llvm::HexagonTargetObjectFile::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#af74245f7fce2e423d6a6b11e6ec37847">anonymous{X86MCInstLower.cpp}::X86MCInstLower::GetSymbolFromOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#ab64771f762bdb53411b08c38f9d7b125">llvm::HexagonTargetObjectFile::SelectSectionForGlobal</a>.</p>

</div>
</div>

### hasLinkOnceAnyLinkage() {#a3acdc3a8bbb5f15edd761e8aee3e2dfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasLinkOnceAnyLinkage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#a0dc5c71cdefd415dcc8569ae3f2b7892">isLinkOnceAnyLinkage</a>.</p>

</div>
</div>

### hasLinkOnceLinkage() {#a091e6599599c4e668373e0feefa92c01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasLinkOnceLinkage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#a4f4d5111c78b4b976e362d12f01ad782">isLinkOnceLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#a082d0b0afa7b05bf751feabbc3550f2b">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::emitArrayBound</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a2773eb6f0be68426806ef8f68bdd4393">llvm::AsmPrinter::emitGlobalAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#ab7906bdf774a35b56cb2e908d012472c">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#aa66476422470ab204074b3198bcf4d15">llvm::JITSymbolFlags::fromGlobalValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/extractgv-cpp/#aecd7db67c15393462f7d55af64644142">makeVisible</a>, <a href="/web-llvm/docs/api/classes/anonymous-linkmodules-cpp-/modulelinker/#a589fd28f47f98110e06d544523d59977">anonymous{LinkModules.cpp}::ModuleLinker::run</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#a0062c60d49f66bddf4bc7fc76ce2968f">shouldRecordVTableAddr</a>.</p>

</div>
</div>

### hasLinkOnceODRLinkage() {#ae28d149d03a6ae88267f649bc1dbe42c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasLinkOnceODRLinkage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#af4663ee02ad0f28a78539ec85c91bec0">isLinkOnceODRLinkage</a>.</p>


<p>Referenced by <a href="#ae3a42354a5b89aa8ade55dab229036f6">canBeOmittedFromSymbolTable</a>.</p>

</div>
</div>

### hasLocalLinkage() {#a3ba1af4b9d9faa4a33729bbbecee83d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasLocalLinkage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#a308b65a044b4f53e31a2026a81c991d2">isLocalLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxasmprinter-cpp/#af8ddf23c91f9cc1ae1e1d4ff1a133259">canDemoteGlobalVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7414a7c636bc5a30b0e8478019a1bcd4">llvm::canTrackGlobalVariableInterprocedurally</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a8d0a2ebeeedeb0bd16a52affb7f6ed88">llvm::Attributor::checkForAllCallSites</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#aeac390246bd74f8e7897e99b30ae2c6f">llvm::MCResourceInfo::createTotalNumSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a6fa44a1fa346266bc9d287dce014dcfb">llvm::MCResourceInfo::createTotalNumVGPRs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5a50ba4ab5027d4013cf6bc2edf66085">deleteIfDead</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a2773eb6f0be68426806ef8f68bdd4393">llvm::AsmPrinter::emitGlobalAlias</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/splitmodule-cpp/#ab04f963f804d27e1b7d7c9b9cfcacb9e">externalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a6d232c3c6e60c94891fffed1f9277e8a">llvm::anonymous{AMDGPUSplitModule.cpp}::externalize</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#ae36c2a9293b9a50a2870d02f93d7d202">llvm::RecordStreamer::flushSymverDirectives</a>, <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp/#a682c8b1a578622031f16f4be7766b603">forceRenaming</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#aa66476422470ab204074b3198bcf4d15">llvm::JITSymbolFlags::fromGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a3681fb2c471c1278bfd939456c752f22">llvm::MCResourceInfo::gatherResourceInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a3e7ee01bba0aa270863ab1e06502f374">llvm::TargetLoweringObjectFileMachO::getCFIPersonalitySymbol</a>, <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#aba31a0ce1b4f3f1ff4f3fba69d6231f7">anonymous{IRSymtab.cpp}::Builder::getComdatIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#acf4019263b41c295bc55032dd651b6e4">llvm::HexagonTargetObjectFile::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a66ebd2ccd2ea699bd04b40dd95c2fee4">llvm::TargetLoweringObjectFileMachO::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#ad06b99b6c5abffb1da312f75775f2f08">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getKnownStateFromValue</a>, <a href="/web-llvm/docs/api/classes/llvm/globalsaaresult/#a47a153bee62e58a430f7da8a31c1ed96">llvm::GlobalsAAResult::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcelftargetobjectfile/#a953050dfdd0d33bc59eb08438aa5d88c">llvm::SparcELFTargetObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a726934c33655de3d8c59b38d0e946a62">llvm::TargetLoweringObjectFileELF::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#ae41814965809c6fb6403ca6338710a25">llvm::TargetLoweringObjectFileMachO::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a23cf1bbd780f1998b4c61acbf5a35a78">hasOnlyColdCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ab084a1deda97f9a90c7c8074c4e6ac6f">inferDSOLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#aab3a49dcff02cbc78628deef02c53296">llvm::HexagonTargetObjectFile::isGlobalInSmallSection</a>, <a href="#a2df2f2e94b5493e9434dbf1c483dbc72">isImplicitDSOLocal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb5dc4f19ccfe906a67745d10a39b4c6">llvm::isIRPGOFlagSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a7fcfddcf483c0b43f2614b2b292f0393">isNonRenamableLocal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/extractgv-cpp/#aecd7db67c15393462f7d55af64644142">makeVisible</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a99e004d21cf0169cd780274146e9f773">mayHaveOtherReferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a8d20a7c0aa0ef76c738e2ca9e21d35d5">OptimizeGlobalVars</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5cb8771722bfd8bcbdeb391b17e6cfd6">processGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#acf172e841018fd16e65771f5ade0b297">replace</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmergeimpl/#a9fbe2dcb11cb3bb78be4d97f388b0c5d">anonymous{GlobalMerge.cpp}::GlobalMergeImpl::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/partiallyinlinelibcalls-cpp/#a0e177ca37bd9b11680cecf99d1115c35">runPartiallyInlineLibCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a60823e6b4ff77b319b51c9eb634241e2">llvm::ExecutionEngine::runStaticConstructorsDestructors</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#ab64771f762bdb53411b08c38f9d7b125">llvm::HexagonTargetObjectFile::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#ac2b50ec3a5402b3063da7211a176f8ff">llvm::XCoreTargetObjectFile::SelectSectionForGlobal</a>, <a href="#a40c699aba3d6b469357ef0b4e1aa2580">setDLLStorageClass</a>, <a href="#aa242d8ab89216c14beab812e07009b2a">setVisibility</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a004b3a18ad13375ad40e88cd41a0fe97">shouldConvertToRelLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#a0062c60d49f66bddf4bc7fc76ce2968f">shouldRecordVTableAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#afc379e94b702009982a10bb57c4a9e7a">llvm::Attributor::shouldUpdateAA</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#ab56b58aa044c07dc0bea0c0662c9d2ae">shouldUsePublicSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a0706966ac4f391854346bebfcda816fa">llvm::anonymous{AMDGPUSplitModule.cpp}::splitAMDGPUModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#af376f4f0e0b55e40407912678b736863">SRAGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4f18aa17f81c88c8fa89c76563a6d510">tryWidenGlobalArraysUsedByMemcpy</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a0ab0b4e3b20c68f71d543a2eb6a32ddf">upgradeDLLImportExportLinkage</a>.</p>

</div>
</div>

### hasPartition() {#a0bf930687efa9a6cdc47d318dbd2e6d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasPartition ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#a1b2401e912b1044a4baf7a5a926968e4">HasPartition</a>.</p>


<p>Referenced by <a href="#a72237a63b5edcf78a32453822139f1d5">getPartition</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a89d2a6c720f05584135f01f20cc3c9ee">anonymous{AsmWriter.cpp}::AssemblyWriter::printIFunc</a> and <a href="#aff8740863a5ee2650339400236b6224b">setPartition</a>.</p>

</div>
</div>

### hasPrivateLinkage() {#a3ed4c5535997ad77ffee00f92430b576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasPrivateLinkage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#a81812ab49218fff82c3a0c378e0a65b0">isPrivateLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a2773eb6f0be68426806ef8f68bdd4393">llvm::AsmPrinter::emitGlobalAlias</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac9d0f2b6d9ec3c966243a29f8c8c7494">getADAEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#acf4019263b41c295bc55032dd651b6e4">llvm::HexagonTargetObjectFile::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a1d07788150d8bd44cbba78db405f1574">llvm::TargetLoweringObjectFileCOFF::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#ab61c33276b67ea22d0ad922a545ced9a">llvm::TargetLoweringObjectFileCOFF::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#af25263afe4b2685f4571b432ced7d171">llvm::TargetMachine::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ace2885fc42e68606f270bfd3180d5f26">isLeakCheckerRoot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#ab64771f762bdb53411b08c38f9d7b125">llvm::HexagonTargetObjectFile::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5835f5de3b78527c3348c7346c197b69">llvm::TargetLoweringObjectFileCOFF::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#afc576f8a8ddd42537a82e1cedc179ae1">tocDataChecks</a>.</p>

</div>
</div>

### hasProtectedVisibility() {#af6d775e717aaa2d1916bccb2ff8778e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasProtectedVisibility ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a9141f967188383108a69cc1b8ed3c195ae1cc9a390520055573d459de25747caa">ProtectedVisibility</a> and <a href="#a4b20bb41f6274a04399a83a821869ad1">Visibility</a>.</p>

</div>
</div>

### hasSanitizerMetadata() {#a6d863ff0d778248ac9b693db3494565c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasSanitizerMetadata ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#a07e6feb9f188917f8dc965f78317f181">HasSanitizerMetadata</a>.</p>


<p>Referenced by <a href="#a10dbf1e2be9c60af49efb9bfded99225">getSanitizerMetadata</a>, <a href="#a40631ccf8ca06c1942f13f4872ed8e86">isTagged</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>.</p>

</div>
</div>

### hasSection() {#a9f52d196211845d0d605733e2f699055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasSection ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="#a7215706ede5f29b81e4f99af35e87aa6">getSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a7fcfddcf483c0b43f2614b2b292f0393">isNonRenamableLocal</a>.</p>

</div>
</div>

### hasValidDeclarationLinkage() {#a334704e7c859bd7c44ca86249a6280cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasValidDeclarationLinkage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#a9a2053e12c56247022b52ffd370ec70d">isValidDeclarationLinkage</a>.</p>

</div>
</div>

### hasWeakAnyLinkage() {#a61afb04130343acdd861174587400c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasWeakAnyLinkage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#a0918c134c7b8131fa37df98101cd17db">isWeakAnyLinkage</a>.</p>

</div>
</div>

### hasWeakLinkage() {#aaca0b3e9845b2fa35c965edaabd5c6bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasWeakLinkage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#ad48190a47d8af6ce16465cda531725a9">isWeakLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#a082d0b0afa7b05bf751feabbc3550f2b">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::emitArrayBound</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a2773eb6f0be68426806ef8f68bdd4393">llvm::AsmPrinter::emitGlobalAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#ab7906bdf774a35b56cb2e908d012472c">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::emitGlobalVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#aa66476422470ab204074b3198bcf4d15">llvm::JITSymbolFlags::fromGlobalValue</a>.</p>

</div>
</div>

### hasWeakODRLinkage() {#ab241086cb8a1e3f7e77fb00c9a8aeb2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::hasWeakODRLinkage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#a39cdc71d12722bb912f3a299ab5574ab">isWeakODRLinkage</a>.</p>

</div>
</div>

### isAbsoluteSymbolRef() {#a3edc4a0cb9df73b6f94a21a51d3c8cf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GlobalValue::isAbsoluteSymbolRef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns whether this is a reference to an absolute symbol.</p>

<p>Declaration at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### isDeclaration() {#a32e606ac4c88f71f14212e42b808e7f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GlobalValue::isDeclaration ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the primary definition of this global value is outside of the current translation unit.</p>

<p>Declaration at line 617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#afca73617f8390579ca48fa10bf1c8edb">assureFPCallStub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a49170e37072dd286a1fcf76f2efec373">llvm::buildModuleSummaryIndex</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a3a5262b6225fdc05cfea242647c56db6">anonymous{WholeProgramDevirt.cpp}::DevirtModule::buildTypeIdentifierMap</a>, <a href="#aa63851a5f68b64cf93d3f8c4a973f33d">canBenefitFromLocalAlias</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a440c7b43772713f767d18f81c9caadf2">llvm::Attributor::checkForAllInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af97d9ff977792ae671987a9a95f942f2">llvm::CloneFunctionBodyInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac1b2be839460bb277d4f07f4aa5225ac">llvm::CloneFunctionInto</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a4aacbb0606ccb384dd6803bdf975eed7">anonymous{ExpandVariadics.cpp}::ExpandVariadics::defineVariadicWrapper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5a50ba4ab5027d4013cf6bc2edf66085">deleteIfDead</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a673ca077823c034cab2b172947847f19">llvm::AMDGPUAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a0202522d1384c2ad88417c496ae62068">llvm::WebAssemblyAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a78e5ec9027384598a0ce9fb4eb3cea72">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4b27e8ffe711b0dcbc16b19671d5edc">llvm::emitLinkerFlagsForGlobalCOFF</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#a55d48bbf1a37a033d78e4e8b7c26cfb9">anonymous{StackSafetyAnalysis.cpp}::findCalleeInModule</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#abcc4f77c7dbf7ed1f581b3773bc0f2df">llvm::ExecutionEngine::FindGlobalVariableNamed</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#acddb0d15dc6d53316188968e5acbefc7">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getNonKernelsWithLDSArguments</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackerfunction/#ab0a8c344bd57a953ec6b9327a443b2b0">anonymous{OpenMPOpt.cpp}::AAICVTrackerFunction::getValueForCall</a>, <a href="#a52355f8a15cd7cedfe83bd82b59e942a">hasExactDefinition</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a1c66d4eff947253e7610a66379974d63">llvm::GlobalVariable::hasInitializer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa730b58924baf8f35394c2e5a0bb3714">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctions</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#ae0bf03df2431c543590180658ce4709d">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctionsWithPriority</a>, <a href="#a6b66f492cbea5f4b4f434d7178477116">isDeclarationForLinker</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a3d10b9d22b94edf6deb16010eb260cdc">IsEmptyAtExitFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetobjectfile/#aa748aed9bae156d6952b2695928bafc4">llvm::MipsTargetObjectFile::IsGlobalInSmallSection</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetobjectfile/#abf75c3694d93018762e04b063152b4ba">llvm::LanaiTargetObjectFile::isGlobalInSmallSection</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#a2adf1ff4e0a2e37ff5c9ebb3c68ea93e">llvm::RISCVELFTargetObjectFile::isGlobalInSmallSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb5dc4f19ccfe906a67745d10a39b4c6">llvm::isIRPGOFlagSet</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadargumentelimination-cpp-/#a13fbf5cf617b7f23022dbc57577d7d39">anonymous{DeadArgumentElimination.cpp}::isMustTailCalleeAnalyzable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a365173e63bd73b3ee58033678429636e">isPotentiallyReachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a766df1ea3c4bf3cbc8586f310562034f">isReportingError</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/globalctordtorscraper/#a5f8ea04329212b479fa473a5b324153c">anonymous{LLJIT.cpp}::GlobalCtorDtorScraper::operator()</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a8d20a7c0aa0ef76c738e2ca9e21d35d5">OptimizeGlobalVars</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmergeimpl/#a9fbe2dcb11cb3bb78be4d97f388b0c5d">anonymous{GlobalMerge.cpp}::GlobalMergeImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-irmover-cpp-/irlinker/#a29e247c718172acd518f8bb0255ff851">anonymous{IRMover.cpp}::IRLinker::run</a>, <a href="/web-llvm/docs/api/structs/llvm/inlinecostannotationprinterpass/#aa0abf6fac51bc051d817b1f71c921098">llvm::InlineCostAnnotationPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a40b5636c9d406c277f51dcdcba06821f">anonymous{ExpandVariadics.cpp}::ExpandVariadics::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a60823e6b4ff77b319b51c9eb634241e2">llvm::ExecutionEngine::runStaticConstructorsDestructors</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/#afd0b41d4bbaf15bfb701ed8eebd2a5c2">anonymous{OpenMPOpt.cpp}::OMPInformationCache::runtimeFnsAvailable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a484621a748732e2f39e7a2a0058b3b07">llvm::stripDebugifyMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#aae5f020a66b7a61f16cf63e17fa31e56">anonymous{StructuralHash.cpp}::StructuralHashImpl::update</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfocallsiteargument/#afd64f56df116f9c6c4763b55bf74897a">anonymous{AttributorAttributes.cpp}::AAPointerInfoCallSiteArgument::updateImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a3f77e2cab72167554d1d13c44fc9877d">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::verifyGraph</a>.</p>

</div>
</div>

### isDeclarationForLinker() {#a6b66f492cbea5f4b4f434d7178477116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isDeclarationForLinker ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#ae76e0b39c563b63554b4c99a8ad726e4">hasAvailableExternallyLinkage</a> and <a href="#a32e606ac4c88f71f14212e42b808e7f4">isDeclaration</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#abfc9f5d963c447cbe28355bc7887d1bd">llvm::X86Subtarget::classifyLocalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ab40658c61a66f761473f4b53aa60dd19">llvm::AsmPrinter::emitXXStructorList</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#ae36c2a9293b9a50a2870d02f93d7d202">llvm::RecordStreamer::flushSymverDirectives</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ae7810a05a90e7fc6d13fa85c0242ab5f">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::getAdjustedFasterLocalExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a2ddf5387f9cd603891e1933c2f84cf65">llvm::TargetLoweringObjectFileXCOFF::getSectionForExternalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a43deb1b2c2e73ff4adac8e70e91b672b">llvm::ARMSubtarget::isGVIndirectSymbol</a>, <a href="#a904b8b68c7e4e888158b03f0eae0e4d5">isStrongDefinitionForLinker</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#aa3f0dc829be1fe9aa1c7d5151db1bf21">llvm::TargetMachine::shouldAssumeDSOLocal</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#ab56b58aa044c07dc0bea0c0662c9d2ae">shouldUsePublicSymbol</a>.</p>

</div>
</div>

### isDefinitionExact() {#a008adb117253c7a0dde2f796be489d65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isDefinitionExact ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the currently visible definition of this global (if any) is exactly the definition we will see at runtime.</p>


<p>Non-exact linkage types inhibits most non-inlining IPO, since a differently optimized variant of the same function can have different observable or undefined behavior than in the variant currently visible. For instance, we could have started with</p>


<p>void foo(int *v) { int t = 5 / v[0]; (void) t; }</p>


<p>and "refined" it to</p>


<p>void foo(int *v) { }</p>


<p>However, we cannot infer readnone for <span class="doxyComputerOutput">foo</span>, since that would justify DSE'ing a store to <span class="doxyComputerOutput">v[0]</span> across a call to <span class="doxyComputerOutput">foo</span>, which can cause undefined behavior if the linker replaces the actual call destination with the unoptimized <span class="doxyComputerOutput">foo</span>.</p>


<p>Inlining is okay across non-exact linkage types as long as they're not interposable (see <span class="doxyComputerOutput">isInterposable</span>), since in such cases the currently visible variant is <em>a</em> correct implementation of the original source function; it just isn't the <em>only</em> correct implementation.</p>


<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Referenced by <a href="#a52355f8a15cd7cedfe83bd82b59e942a">hasExactDefinition</a>.</p>

</div>
</div>

### isDiscardableIfUnused() {#a863b49cf36a53aa979a81c6e10c4d6b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isDiscardableIfUnused ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#a863b49cf36a53aa979a81c6e10c4d6b5">isDiscardableIfUnused</a>.</p>


<p>Referenced by <a href="#a863b49cf36a53aa979a81c6e10c4d6b5">isDiscardableIfUnused</a>.</p>

</div>
</div>

### isDSOLocal() {#a19db81b6f3d3ab342972dce7756fb077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isDSOLocal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#abbf8c73bfeef429bbf6f5d1ae346893b">IsDSOLocal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a49170e37072dd286a1fcf76f2efec373">llvm::buildModuleSummaryIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#af3c010276b401e92a124e50fcef97fe1">llvm::GlobalObject::canIncreaseAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#a101d392f12933ec345c1cef1f552809e">copyLinkageVisibility</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#a55d48bbf1a37a033d78e4e8b7c26cfb9">anonymous{StackSafetyAnalysis.cpp}::findCalleeInModule</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a9a1560129bcae4e7e2456326461a8aa6">llvm::AsmPrinter::getSymbolPreferLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#abb09db483ec58bc265994fd4924592d5">llvm::ARMSubtarget::isGVInGOT</a>, <a href="#aa1558e13ceef68db8ea9f4e3b5a64cbd">isInterposable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a6c0ba55113b40b07b869ba9c06db6ca1">OptimizeGlobalAliases</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ae205407d61d26187ae589c4a4f78320e">PrintDSOLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#aa3f0dc829be1fe9aa1c7d5151db1bf21">llvm::TargetMachine::shouldAssumeDSOLocal</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a004b3a18ad13375ad40e88cd41a0fe97">shouldConvertToRelLookupTable</a>.</p>

</div>
</div>

### isImplicitDSOLocal() {#a2df2f2e94b5493e9434dbf1c483dbc72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isImplicitDSOLocal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3e6237ebf8cf834ae6fa726efccaef8d">hasDefaultVisibility</a>, <a href="#a51af265dc931258cdb8ffb37ee6decee">hasExternalWeakLinkage</a> and <a href="#a3ba1af4b9d9faa4a33729bbbecee83d1">hasLocalLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3e9604d679f4806943544dceaeb68149">llvm::convertToDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a6c0ba55113b40b07b869ba9c06db6ca1">OptimizeGlobalAliases</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ae205407d61d26187ae589c4a4f78320e">PrintDSOLocation</a>, <a href="#a687973de03d041e04b50a76d19d4fd36">setLinkage</a>, <a href="#aa242d8ab89216c14beab812e07009b2a">setVisibility</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a004b3a18ad13375ad40e88cd41a0fe97">shouldConvertToRelLookupTable</a>.</p>

</div>
</div>

### isInterposable() {#aa1558e13ceef68db8ea9f4e3b5a64cbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GlobalValue::isInterposable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this global's definition can be substituted with an <em>arbitrary</em> definition at link time or load time.</p>


<p>We cannot do any IPO or inlining across interposable call edges, since the callee can be replaced with something arbitrary.</p>


<p>Declaration at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a>, <a href="#a739b30c811f1eece61b05320ddf44e5b">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a344446b3349dc1d73464b3bb5ae0e6bf">llvm::Module::getSemanticInterposition</a>, <a href="#a19db81b6f3d3ab342972dce7756fb077">isDSOLocal</a> and <a href="#aabf6932ed41fc64e17c0030c44eda44e">isInterposableLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#a55d48bbf1a37a033d78e4e8b7c26cfb9">anonymous{StackSafetyAnalysis.cpp}::findCalleeInModule</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#aec2d700d8b1e57f830a673c39a1f30dc">llvm::GlobalVariable::hasDefinitiveInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a81bb5b0675c34a74c62b2547865c8d7b">llvm::ObjectSizeOffsetVisitor::visitGlobalAlias</a> and <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a29d90faf3dd7128f83eca30377481bfe">llvm::ObjectSizeOffsetVisitor::visitGlobalVariable</a>.</p>

</div>
</div>

### isStrongDefinitionForLinker() {#a904b8b68c7e4e888158b03f0eae0e4d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isStrongDefinitionForLinker ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this global's definition will be the one chosen by the linker.</p>


<p>NB! Ideally this should not be used at the IR level at all. If you're interested in optimization constraints implied by the linker's ability to choose an implementation, prefer using <span class="doxyComputerOutput">hasExactDefinition</span>.</p>


<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a6b66f492cbea5f4b4f434d7178477116">isDeclarationForLinker</a> and <a href="#ac0495132fc83c026033c62c59b30489f">isWeakForLinker</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a43a17d867ea4d3bca00dfb065f8cc811">callsShareTOCBase</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#af3c010276b401e92a124e50fcef97fe1">llvm::GlobalObject::canIncreaseAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#ad9379319a0f19f0c42b5ee18d9f02373">llvm::GlobalVariable::hasUniqueInitializer</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#aa3f0dc829be1fe9aa1c7d5151db1bf21">llvm::TargetMachine::shouldAssumeDSOLocal</a>.</p>

</div>
</div>

### isTagged() {#a40631ccf8ca06c1942f13f4872ed8e86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isTagged ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a10dbf1e2be9c60af49efb9bfded99225">getSanitizerMetadata</a>, <a href="#a6d863ff0d778248ac9b693db3494565c">hasSanitizerMetadata</a> and <a href="/web-llvm/docs/api/structs/llvm/globalvalue/sanitizermetadata/#a06dd653fcfff7260ea2ab89cc39029cb">llvm::GlobalValue::SanitizerMetadata::Memtag</a>.</p>


<p>Referenced by <a href="#aa63851a5f68b64cf93d3f8c4a973f33d">canBenefitFromLocalAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#aa2bf24e995494a7c64d8f3e02818ad30">llvm::AArch64Subtarget::ClassifyGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a> and <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmergeimpl/#a9fbe2dcb11cb3bb78be4d97f388b0c5d">anonymous{GlobalMerge.cpp}::GlobalMergeImpl::run</a>.</p>

</div>
</div>

### isThreadLocal() {#a239427c2c3a01e23bd15b29633696536}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isThreadLocal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the value is "Thread Local", its value isn't shared by the threads.</p>

<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a52126ae2091b18cecfd5ad0f0012839a">getThreadLocalMode</a> and <a href="#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">NotThreadLocal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#ab7906bdf774a35b56cb2e908d012472c">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#ab98a836a506bb90245c243f8e4da3162">llvm::ExecutionEngine::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a0202522d1384c2ad88417c496ae62068">llvm::WebAssemblyAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7ee632093c5fc25ca22faa353105aa74">llvm::SelectionDAG::getGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a2ddf5387f9cd603891e1933c2f84cf65">llvm::TargetLoweringObjectFileXCOFF::getSectionForExternalReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af1ef95140ed897d441343e4a93d37726">isFunctionGlobalAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#a6ebdfd799686fe407798a4d503a41cd9">isUnmergeableGlobal</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcorelowerthreadlocal-cpp-/xcorelowerthreadlocal/#adb1323a587666f6b6a98e4d7c2ba24af">anonymous{XCoreLowerThreadLocal.cpp}::XCoreLowerThreadLocal::lowerGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmergeimpl/#a9fbe2dcb11cb3bb78be4d97f388b0c5d">anonymous{GlobalMerge.cpp}::GlobalMergeImpl::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>.</p>

</div>
</div>

### isWeakForLinker() {#ac0495132fc83c026033c62c59b30489f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isWeakForLinker ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a> and <a href="#ac0495132fc83c026033c62c59b30489f">isWeakForLinker</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#af00c22607d77d29f2f949fe7a1359e5f">getFirstDefinitionForLinker</a>, <a href="#a904b8b68c7e4e888158b03f0eae0e4d5">isStrongDefinitionForLinker</a> and <a href="#ac0495132fc83c026033c62c59b30489f">isWeakForLinker</a>.</p>

</div>
</div>

### removeFromParent() {#ae52ff267989fb6aca697d29dea0cb027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalValue::removeFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method unlinks 'this' from the containing module, but does not delete it.</p>

<p>Declaration at line 651 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#a4a6ca5a5b87bd84231be9d8dbec46c1a">llvm::Value::getValueID</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-irmover-cpp-/irlinker/#a29e247c718172acd518f8bb0255ff851">anonymous{IRMover.cpp}::IRLinker::run</a>.</p>

</div>
</div>

### removeSanitizerMetadata() {#a1b8db417ccdc447464add1a3d9358759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalValue::removeSanitizerMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a1eb8504bab5f794778d82db6ac829923">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a0870bd38114456f0b723d2a5dc741879">llvm::LLVMContextImpl::GlobalValueSanitizerMetadata</a>, <a href="#a07e6feb9f188917f8dc965f78317f181">HasSanitizerMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aa142c8c536b95dd8e8a243cb67b57a80">llvm::LLVMContext::pImpl</a>.</p>


<p>Referenced by <a href="#a96c9558e69f588728273b57eb5a1fe73">copyAttributesFrom</a>.</p>

</div>
</div>

### setDLLStorageClass() {#a40c699aba3d6b469357ef0b4e1aa2580}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalValue::setDLLStorageClass (<a href="#a6948096330886cc831391c75adbadaf8">DLLStorageClassTypes</a> C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a6948096330886cc831391c75adbadaf8a5354f0f932438b7ec4d5d82d4ec1ae22">DefaultStorageClass</a>, <a href="#af89f25d8a89068ab9be05f2a095da4ed">DllStorageClass</a> and <a href="#a3ba1af4b9d9faa4a33729bbbecee83d1">hasLocalLinkage</a>.</p>


<p>Referenced by <a href="#a96c9558e69f588728273b57eb5a1fe73">copyAttributesFrom</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a0ab0b4e3b20c68f71d543a2eb6a32ddf">upgradeDLLImportExportLinkage</a>.</p>

</div>
</div>

### setDSOLocal() {#a78c4d0538c7dbffa955486abae2b61bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalValue::setDSOLocal (bool Local)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#abbf8c73bfeef429bbf6f5d1ae346893b">IsDSOLocal</a> and <a href="#ae8df4be75bfc50b1eadd74e85c25fa45a509820290d57f333403f490dde7316f4">Local</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3e9604d679f4806943544dceaeb68149">llvm::convertToDeclaration</a>, <a href="#a96c9558e69f588728273b57eb5a1fe73">copyAttributesFrom</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#a101d392f12933ec345c1cef1f552809e">copyLinkageVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a4cb54e7d62530f9e973ff35f6301de6a">llvm::X86TargetLowering::getIRStackGuard</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#afb5c7d9f47f77651e28e14b6e715badf">getOrCreateFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ab084a1deda97f9a90c7c8074c4e6ac6f">inferDSOLocal</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#af85fe4610a8ddd0d57149e73008f32fb">llvm::Attributor::internalizeFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp/#a1bbf1b914ac436764ec303507b0dfc77">maybeSetDSOLocal</a>, <a href="#a687973de03d041e04b50a76d19d4fd36">setLinkage</a> and <a href="#aa242d8ab89216c14beab812e07009b2a">setVisibility</a>.</p>

</div>
</div>

### setLinkage() {#a687973de03d041e04b50a76d19d4fd36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalValue::setLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> LT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a6948096330886cc831391c75adbadaf8a5354f0f932438b7ec4d5d82d4ec1ae22">DefaultStorageClass</a>, <a href="#a9141f967188383108a69cc1b8ed3c195a2491e41d821f1d8fd3958ce3df2fddb2">DefaultVisibility</a>, <a href="#af89f25d8a89068ab9be05f2a095da4ed">DllStorageClass</a>, <a href="#a2df2f2e94b5493e9434dbf1c483dbc72">isImplicitDSOLocal</a>, <a href="#a308b65a044b4f53e31a2026a81c991d2">isLocalLinkage</a>, <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>, <a href="#a78c4d0538c7dbffa955486abae2b61bb">setDSOLocal</a> and <a href="#a4b20bb41f6274a04399a83a821869ad1">Visibility</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab371d6b308eb9772bdec63cf7a041407">llvm::CloneModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#a101d392f12933ec345c1cef1f552809e">copyLinkageVisibility</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a61a95dc82ae09814a35f56fcc56cad5b">createMemprofDefaultOptionsVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af0793991541abccfec5c0d8831612b7b">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::createNoAllocVariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#adced657ead8595f4da252cea6e2f3dd8">createProfileFileNameVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd35d43ef05edd633413fa4cfa802c0e">llvm::createProfileFileNameVar</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a0020cbf9c3df714558a9b20a6267bd29">llvm::Function::deleteBody</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/splitmodule-cpp/#ab04f963f804d27e1b7d7c9b9cfcacb9e">externalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a6d232c3c6e60c94891fffed1f9277e8a">llvm::anonymous{AMDGPUSplitModule.cpp}::externalize</a>, <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#a4f0167f2ae072a399680c468a9777221">handleNonPrevailingComdat</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#af85fe4610a8ddd0d57149e73008f32fb">llvm::Attributor::internalizeFunctions</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantglobals/#gad232c5aeae9948d477420a41cc8f696b">LLVMSetLinkage</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/extractgv-cpp/#aecd7db67c15393462f7d55af64644142">makeVisible</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a8d20a7c0aa0ef76c738e2ca9e21d35d5">OptimizeGlobalVars</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphupdater/#a300122a2a53b922943eff21c4039ad73">llvm::CallGraphUpdater::removeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#ac926ba61257c2262ebca3deca2cc8c76">replaceAliasWithAliasee</a>, <a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/sanitizerbinarymetadata/#aeda46a0421732a3d803584285212162f">anonymous{SanitizerBinaryMetadata.cpp}::SanitizerBinaryMetadata::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp/#a8fe56fea0dcbc78bba2366b7e2918a41">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a40b5636c9d406c277f51dcdcba06821f">anonymous{ExpandVariadics.cpp}::ExpandVariadics::runOnFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>.</p>

</div>
</div>

### setNoSanitizeMetadata() {#a9f4c146a2651316c36059560e138d3e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalValue::setNoSanitizeMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>Reference <a href="#add48ed79a5cd63c7165f3f4da102b9fd">setSanitizerMetadata</a>.</p>

</div>
</div>

### setPartition() {#aff8740863a5ee2650339400236b6224b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalValue::setPartition (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Part)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a016dccd2194d0bcf0c171921ac089569">llvm::LLVMContextImpl::GlobalValuePartitions</a>, <a href="#a1b2401e912b1044a4baf7a5a926968e4">HasPartition</a>, <a href="#a0bf930687efa9a6cdc47d318dbd2e6d4">hasPartition</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aa142c8c536b95dd8e8a243cb67b57a80">llvm::LLVMContext::pImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/uniquestringsaver/#aaa37b5fdb34477a1eb3361f7ee9717f3">llvm::UniqueStringSaver::save</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a9b7a55908da35f0359df5eb4279015ca">llvm::LLVMContextImpl::Saver</a>.</p>


<p>Referenced by <a href="#a96c9558e69f588728273b57eb5a1fe73">copyAttributesFrom</a>.</p>

</div>
</div>

### setSanitizerMetadata() {#add48ed79a5cd63c7165f3f4da102b9fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalValue::setSanitizerMetadata (<a href="/web-llvm/docs/api/structs/llvm/globalvalue/sanitizermetadata">SanitizerMetadata</a> Meta)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a0870bd38114456f0b723d2a5dc741879">llvm::LLVMContextImpl::GlobalValueSanitizerMetadata</a>, <a href="#a07e6feb9f188917f8dc965f78317f181">HasSanitizerMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aa142c8c536b95dd8e8a243cb67b57a80">llvm::LLVMContext::pImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#ae277c85704c17a21f772da0aee54fbaa">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::buildNonKernelLDSBaseTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a3c3a71194fc12f9298575a42187928bd">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::buildNonKernelLDSOffsetTable</a>, <a href="#a96c9558e69f588728273b57eb5a1fe73">copyAttributesFrom</a> and <a href="#a9f4c146a2651316c36059560e138d3e9">setNoSanitizeMetadata</a>.</p>

</div>
</div>

### setThreadLocal() {#aef4a60d204c56d074163c4c3a70bc603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalValue::setThreadLocal (bool Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a05c6b3b9372b56d130e005db4837da62a55e32c080bb5217324a597d4fb441660">GeneralDynamicTLSModel</a>, <a href="#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">NotThreadLocal</a> and <a href="#a472652f9e89e006426f371fcbfa6f619">setThreadLocalMode</a>.</p>

</div>
</div>

### setThreadLocalMode() {#a472652f9e89e006426f371fcbfa6f619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalValue::setThreadLocalMode (<a href="#a05c6b3b9372b56d130e005db4837da62">ThreadLocalMode</a> Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a4a6ca5a5b87bd84231be9d8dbec46c1a">llvm::Value::getValueID</a>, <a href="#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">NotThreadLocal</a> and <a href="#acf0096839ddf4913784dfaa716329064">ThreadLocal</a>.</p>


<p>Referenced by <a href="#a96c9558e69f588728273b57eb5a1fe73">copyAttributesFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#af9ea64c7dae47dcfa2c9f5775fb5915d">llvm::GlobalVariable::GlobalVariable</a>, <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalvariable/#ga1862f0ecae626310ed6b8d8401cfd48b">LLVMSetThreadLocalMode</a> and <a href="#aef4a60d204c56d074163c4c3a70bc603">setThreadLocal</a>.</p>

</div>
</div>

### setUnnamedAddr() {#a38c97622dccff7ae31fe0be3b21c9b3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalValue::setUnnamedAddr (<a href="#ae8df4be75bfc50b1eadd74e85c25fa45">UnnamedAddr</a> Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#af8c3ae3e5e774d859ca9b52521a537af">UnnamedAddrVal</a>.</p>


<p>Referenced by <a href="#a96c9558e69f588728273b57eb5a1fe73">copyAttributesFrom</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-jmcinstrumenter-cpp-/#aea6556d942d972a777204187dd1600e5">anonymous{JMCInstrumenter.cpp}::createDefaultCheckFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a15889f1df360601e4f92325b39882a34">llvm::createPrivateGlobalForString</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a1ca1f5b41c1408be83df43ab024cdd69">createRelLookupTable</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#afbf3f5773f08115de0ee332eae1ff187">DataScalarizerVisitor::findAndReplaceVectors</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilflattenarrays-cpp/#ab655865aaad374f00365011edc7440da">flattenGlobalArrays</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantglobals/#gad230665371e05b1baf5b0ba5825036ea">LLVMSetUnnamedAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5cb8771722bfd8bcbdeb391b17e6cfd6">processGlobal</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp/#a8fe56fea0dcbc78bba2366b7e2918a41">runImpl</a>.</p>

</div>
</div>

### setVisibility() {#aa242d8ab89216c14beab812e07009b2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalValue::setVisibility (<a href="#a9141f967188383108a69cc1b8ed3c195">VisibilityTypes</a> V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9141f967188383108a69cc1b8ed3c195a2491e41d821f1d8fd3958ce3df2fddb2">DefaultVisibility</a>, <a href="#a3ba1af4b9d9faa4a33729bbbecee83d1">hasLocalLinkage</a>, <a href="#a2df2f2e94b5493e9434dbf1c483dbc72">isImplicitDSOLocal</a>, <a href="#a78c4d0538c7dbffa955486abae2b61bb">setDSOLocal</a> and <a href="#a4b20bb41f6274a04399a83a821869ad1">Visibility</a>.</p>


<p>Referenced by <a href="#a96c9558e69f588728273b57eb5a1fe73">copyAttributesFrom</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#a101d392f12933ec345c1cef1f552809e">copyLinkageVisibility</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#aab0bb9923065afc9aca06aec133ff91e">anonymous{NVPTXCtorDtorLowering.cpp}::createInitOrFiniGlobals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd35d43ef05edd633413fa4cfa802c0e">llvm::createProfileFileNameVar</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a7db9daa323dee69eb9ecc380ce6edae8">llvm::OpenMPIRBuilder::createTargetInit</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a16a470a2b40fa6e28a35af849806450b">anonymous{WholeProgramDevirt.cpp}::DevirtModule::exportGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/splitmodule-cpp/#ab04f963f804d27e1b7d7c9b9cfcacb9e">externalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a6d232c3c6e60c94891fffed1f9277e8a">llvm::anonymous{AMDGPUSplitModule.cpp}::externalize</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#aeaa8e35cfb5c615f98eeaeeb9ab62788">anonymous{WholeProgramDevirt.cpp}::DevirtModule::importGlobal</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#af85fe4610a8ddd0d57149e73008f32fb">llvm::Attributor::internalizeFunctions</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/extractgv-cpp/#aecd7db67c15393462f7d55af64644142">makeVisible</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/globalctordtorscraper/#a5f8ea04329212b479fa473a5b324153c">anonymous{LLJIT.cpp}::GlobalCtorDtorScraper::operator()</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a727a05f1cb9b333d251bd1485784d039">anonymous{ThinLTOBitcodeWriter.cpp}::promoteInternals</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#ac926ba61257c2262ebca3deca2cc8c76">replaceAliasWithAliasee</a>, <a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/sanitizerbinarymetadata/#aeda46a0421732a3d803584285212162f">anonymous{SanitizerBinaryMetadata.cpp}::SanitizerBinaryMetadata::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a40b5636c9d406c277f51dcdcba06821f">anonymous{ExpandVariadics.cpp}::ExpandVariadics::runOnFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd3c2c7d03f515419a1785e0a2eb6ea8">llvm::setPGOFuncVisibility</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### copyAttributesFrom() {#a96c9558e69f588728273b57eb5a1fe73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalValue::copyAttributesFrom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * Src)</td>
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

<p>Copy all additional attributes (those not needed to create a <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a>) from the <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> Src to this one.</p>


<p>copyAttributesFrom - copy all additional attributes (those not needed to create a <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a>) from the <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> Src to this one.</p>


<p>Declaration at line 558 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a>, <a href="#a1b8db417ccdc447464add1a3d9358759">removeSanitizerMetadata</a>, <a href="#a40c699aba3d6b469357ef0b4e1aa2580">setDLLStorageClass</a>, <a href="#a78c4d0538c7dbffa955486abae2b61bb">setDSOLocal</a>, <a href="#aff8740863a5ee2650339400236b6224b">setPartition</a>, <a href="#add48ed79a5cd63c7165f3f4da102b9fd">setSanitizerMetadata</a>, <a href="#a472652f9e89e006426f371fcbfa6f619">setThreadLocalMode</a>, <a href="#a38c97622dccff7ae31fe0be3b21c9b3d">setUnnamedAddr</a> and <a href="#aa242d8ab89216c14beab812e07009b2a">setVisibility</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalalias/#ae7c767109f051b172dd61a1c18735749">llvm::GlobalAlias::copyAttributesFrom</a> and <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a92be15c3c916aa2e05b5485075882947">llvm::GlobalObject::copyAttributesFrom</a>.</p>

</div>
</div>

### getGlobalValueSubClassData() {#aaf6a02ecb2b904406b783da5bfd6564e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValue::getGlobalValueSubClassData ()</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a115ac0121663aa8365e095d095d0c633">llvm::GlobalObject::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a0a1244217eda4d01f9891f6c2dca7a9f">llvm::GlobalVariable::getCodeModelRaw</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#ad9662340b952dc803605bf33a28cada6">llvm::GlobalObject::getGlobalObjectSubClassData</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#ade7dc7510e950cd1c1181138b390f965">llvm::GlobalObject::hasSection</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a49b398b1c83ef4d42c8f7756b443f61f">llvm::GlobalObject::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a744c0517c37679d036cc7f381a12f60f">llvm::GlobalObject::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#ac2b82881a2653d3ec234491e0c84ea71">llvm::GlobalVariable::setCodeModel</a> and <a href="/web-llvm/docs/api/classes/llvm/globalobject/#ad10eefb0fa57d440583a1dc2abbd4e1e">llvm::GlobalObject::setGlobalObjectSubClassData</a>.</p>

</div>
</div>

### setGlobalValueSubClassData() {#ab4e766c05dc79278ee675263c13c1cb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalValue::setGlobalValueSubClassData (unsigned V)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a9a95237a18eb8cdb7f4d1aa99d6120b0">GlobalValueSubClassDataBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a5b53de0b76d2880fb3e4b487cb4fee75">llvm::GlobalObject::GlobalObject</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a49b398b1c83ef4d42c8f7756b443f61f">llvm::GlobalObject::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a744c0517c37679d036cc7f381a12f60f">llvm::GlobalObject::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#ac2b82881a2653d3ec234491e0c84ea71">llvm::GlobalVariable::setCodeModel</a> and <a href="/web-llvm/docs/api/classes/llvm/globalobject/#ad10eefb0fa57d440583a1dc2abbd4e1e">llvm::GlobalObject::setGlobalObjectSubClassData</a>.</p>

</div>
</div>

### setParent() {#a61c5cb86cc6dbf8bf883170689b421a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalValue::setParent (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * parent)</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Reference <a href="#acb71c8012dfaa189618d2cdafb58b4b0">Parent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### destroyConstantImpl() {#a2ad45ad67b9df38e12261c3675e9824c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalValue::destroyConstantImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Override destroyConstantImpl to make sure it doesn't get called on <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a>'s because they shouldn't be treated like other constants.</p>

<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>

</div>
</div>

### handleOperandChangeImpl() {#a12aa05338951522d7c3936a091f4704a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * GlobalValue::handleOperandChangeImpl (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * From, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>

</div>
</div>

### isNobuiltinFnDef() {#a94dab11fc3e2662aac0663913381551f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GlobalValue::isNobuiltinFnDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the global is a function definition with the nobuiltin attribute.</p>

<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>

</div>
</div>

### mayBeDerefined() {#a68b1bf0587e314cad8ab83618f9d9bad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::mayBeDerefined ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the definition of this global may be replaced by a differently optimized variant of the same source level function at link time.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### DllStorageClass {#af89f25d8a89068ab9be05f2a095da4ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValue::DllStorageClass</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Referenced by <a href="#af09a662b4e302d0683d0fe9dc2a9335f">getDLLStorageClass</a>, <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a>, <a href="#a6a94ead7cfc2b5b3c035be6fe7b52a4f">hasDLLExportStorageClass</a>, <a href="#a66501d6d43642a526ab769458d700aa4">hasDLLImportStorageClass</a>, <a href="#a40c699aba3d6b469357ef0b4e1aa2580">setDLLStorageClass</a> and <a href="#a687973de03d041e04b50a76d19d4fd36">setLinkage</a>.</p>

</div>
</div>

### HasLLVMReservedName {#a53750bb517b7bfc28013f16cdbe2de4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValue::HasLLVMReservedName</td>
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

<p>True if the function's name starts with "llvm.".</p>


<p>This corresponds to the value of <a href="/web-llvm/docs/api/classes/llvm/function/#a900a32da3983469187b1848189681705">Function::isIntrinsic()</a>, which may be true even if Function::intrinsicID() returns <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226">Intrinsic::not_intrinsic</a>.</p>


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Referenced by <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#a900a32da3983469187b1848189681705">llvm::Function::isIntrinsic</a>.</p>

</div>
</div>

### HasPartition {#a1b2401e912b1044a4baf7a5a926968e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValue::HasPartition</td>
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

<p>True if this symbol has a partition name assigned (see <a href="https://lld.llvm.org/Partitions.html">https://lld.llvm.org/Partitions.html</a>).</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Referenced by <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a>, <a href="#a0bf930687efa9a6cdc47d318dbd2e6d4">hasPartition</a> and <a href="#aff8740863a5ee2650339400236b6224b">setPartition</a>.</p>

</div>
</div>

### HasSanitizerMetadata {#a07e6feb9f188917f8dc965f78317f181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValue::HasSanitizerMetadata</td>
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

<p>True if this symbol has sanitizer metadata available.</p>


<p>Should only happen if sanitizers were enabled when building the translation unit which contains this GV.</p>


<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Referenced by <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a>, <a href="#a6d863ff0d778248ac9b693db3494565c">hasSanitizerMetadata</a>, <a href="#a1b8db417ccdc447464add1a3d9358759">removeSanitizerMetadata</a> and <a href="#add48ed79a5cd63c7165f3f4da102b9fd">setSanitizerMetadata</a>.</p>

</div>
</div>

### IntID {#a4fb893b6154100a981579b7b5cb3e638}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Intrinsic::ID llvm::GlobalValue::IntID = (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a>)0U</td>
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

<p>The intrinsic <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for this subclass (which must be a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>).</p>


<p>This member is defined by this class, but not used for anything. Subclasses can use it to store their intrinsic <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, if they have one.</p>


<p>This is stored here to save space in <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> on 64-bit hosts.</p>


<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/function/#a4d0a7baab8d078065b2de10e3460892a">llvm::Function::getIntrinsicID</a>.</p>

</div>
</div>

### IsDSOLocal {#abbf8c73bfeef429bbf6f5d1ae346893b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValue::IsDSOLocal</td>
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

<p>If true then there is a definition within the same linkage unit and that definition cannot be runtime preempted.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Referenced by <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a>, <a href="#a19db81b6f3d3ab342972dce7756fb077">isDSOLocal</a> and <a href="#a78c4d0538c7dbffa955486abae2b61bb">setDSOLocal</a>.</p>

</div>
</div>

### Linkage {#ad61abcbd08169ff119e819ef0482744d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValue::Linkage</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/function/#a7321f6163cd0a3ed2c1e87c63c6c4263">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#ab815632298cb8e2271e2a0e7062a7360">llvm::GlobalAlias::create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a1726164ac15b6aa13ed5bbdd07f0a576">llvm::GlobalAlias::create</a>, <a href="#a9f44684437922cc04a01fcdcc73215d0">getGlobalIdentifier</a>, <a href="#a3547d58a060ee2e4a29cbea85bef91af">getLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a5b53de0b76d2880fb3e4b487cb4fee75">llvm::GlobalObject::GlobalObject</a>, <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a>, <a href="#a0b09f704d0928e6811660fa3af8f626c">isAppendingLinkage</a>, <a href="#a578061260691a59a9e7b0455fd68359c">isAvailableExternallyLinkage</a>, <a href="#a76d750f65089b2e70a927cf9d275a9d7">isCommonLinkage</a>, <a href="#adcb86d621c23938671ad526d3bd1f9bd">isDiscardableIfUnused</a>, <a href="#a89a664b58385307fbb24c02e141d864b">isExternalLinkage</a>, <a href="#a25e8e3490a28e9178b302b76ae643443">isExternalWeakLinkage</a>, <a href="#a9bbb20d12147495c229051feded37cdc">isInternalLinkage</a>, <a href="#aabf6932ed41fc64e17c0030c44eda44e">isInterposableLinkage</a>, <a href="#a0dc5c71cdefd415dcc8569ae3f2b7892">isLinkOnceAnyLinkage</a>, <a href="#a4f4d5111c78b4b976e362d12f01ad782">isLinkOnceLinkage</a>, <a href="#af4663ee02ad0f28a78539ec85c91bec0">isLinkOnceODRLinkage</a>, <a href="#a308b65a044b4f53e31a2026a81c991d2">isLocalLinkage</a>, <a href="#a81812ab49218fff82c3a0c378e0a65b0">isPrivateLinkage</a>, <a href="#a9a2053e12c56247022b52ffd370ec70d">isValidDeclarationLinkage</a>, <a href="#a0918c134c7b8131fa37df98101cd17db">isWeakAnyLinkage</a>, <a href="#ac291102760c543c8e045e829d57d3341">isWeakForLinker</a>, <a href="#ad48190a47d8af6ce16465cda531725a9">isWeakLinkage</a>, <a href="#a39cdc71d12722bb912f3a299ab5574ab">isWeakODRLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a4b5d91825bd05a14280768680626e294">llvm::GlobalAlias::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/globalifunc/#ad6c45f7f1a94365f2db760f61a3b2d3d">llvm::GlobalIFunc::operator=</a>, <a href="#a687973de03d041e04b50a76d19d4fd36">setLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalifunc/#aa096b32e127043e3d34a2eec20637a71">llvm::GlobalIFunc::SymbolTableListTraits&lt; GlobalIFunc &gt;</a>.</p>

</div>
</div>

### Parent {#acb71c8012dfaa189618d2cdafb58b4b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module* llvm::GlobalValue::Parent = nullptr</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalobject/#af3c010276b401e92a124e50fcef97fe1">llvm::GlobalObject::canIncreaseAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a1726164ac15b6aa13ed5bbdd07f0a576">llvm::GlobalAlias::create</a>, <a href="#a739b30c811f1eece61b05320ddf44e5b">getParent</a>, <a href="#a0a3012859837d61e5de0037879333749">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a4b5d91825bd05a14280768680626e294">llvm::GlobalAlias::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/globalifunc/#ad6c45f7f1a94365f2db760f61a3b2d3d">llvm::GlobalIFunc::operator=</a>, <a href="#a61c5cb86cc6dbf8bf883170689b421a7">setParent</a> and <a href="/web-llvm/docs/api/classes/llvm/globalifunc/#aa096b32e127043e3d34a2eec20637a71">llvm::GlobalIFunc::SymbolTableListTraits&lt; GlobalIFunc &gt;</a>.</p>

</div>
</div>

### ThreadLocal {#acf0096839ddf4913784dfaa716329064}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValue::ThreadLocal</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Referenced by <a href="#a52126ae2091b18cecfd5ad0f0012839a">getThreadLocalMode</a>, <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a> and <a href="#a472652f9e89e006426f371fcbfa6f619">setThreadLocalMode</a>.</p>

</div>
</div>

### UnnamedAddrVal {#af8c3ae3e5e774d859ca9b52521a537af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValue::UnnamedAddrVal</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Referenced by <a href="#ac2417a3c6edd0db7a9ad84b82c4054b7">getUnnamedAddr</a>, <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a> and <a href="#a38c97622dccff7ae31fe0be3b21c9b3d">setUnnamedAddr</a>.</p>

</div>
</div>

### ValueType {#a177d1baba701de456c801ac1c05979b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::GlobalValue::ValueType</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Referenced by <a href="#af1dd2acfc2950742e41a64a342b15c80">getValueType</a> and <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a>.</p>

</div>
</div>

### Visibility {#a4b20bb41f6274a04399a83a821869ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValue::Visibility</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Referenced by <a href="#a28b9561d9ef3d237ef894023187fa26c">getVisibility</a>, <a href="#af38a8629ae32606b01eacbbd667d831c">GlobalValue</a>, <a href="#a3e6237ebf8cf834ae6fa726efccaef8d">hasDefaultVisibility</a>, <a href="#a50baaf8d8a18c0cda69eb8d8eca178f9">hasHiddenVisibility</a>, <a href="#af6d775e717aaa2d1916bccb2ff8778e9">hasProtectedVisibility</a>, <a href="#a687973de03d041e04b50a76d19d4fd36">setLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#afc31bb8f3573226060a5c31480fa650e">llvm::GlobalObject::setVCallVisibilityMetadata</a> and <a href="#aa242d8ab89216c14beab812e07009b2a">setVisibility</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SubClassData {#a7eaf291fe2fbdfea96c16bc681162aa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValue::SubClassData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#adeb291fef3614d59a1cb130bb73ab024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>

</div>
</div>

### dropLLVMManglingEscape() {#a3e999e4bb7297d284f931638721840e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::GlobalValue::dropLLVMManglingEscape (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>If the given string begins with the <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> name mangling escape character '\1', drop it.</p>


<p>This function applies a specific mangling that is used in PGO profiles, among other things. If you're trying to get a symbol name for an arbitrary <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a>, this is not the function you're looking for; see <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mangler-h">Mangler.h</a>.</p>


<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa849a65237107c0118e25e93a42ab2bd">llvm::DwarfUnit::addLinkageName</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/argument/#a1aa19965a8f70cf0a0848106b1bc885c">llvm::DiagnosticInfoOptimizationBase::Argument::Argument</a>, <a href="/web-llvm/docs/api/classes/llvm/winexception/#aeaa5422d8ee3dd96aca4513a89a94035">llvm::WinException::beginFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a94bbcf6e7814ab7970d3a03436bf2eb4">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::emitFunctionHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp/#ab78e5a2681b144ee04d3e4ae5dbc170e">getMCSymbolForMBB</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#ac623fd2d132c0a19c1b96c76a0821b92">anonymous{LTO.cpp}::InProcessThinBackend::InProcessThinBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adfeaf9db4445cbd2d43f260218036006">recoverFramePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/lto/#ada5eca1803d5afcb1005ea05ffc62636">llvm::lto::LTO::run</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a147437aa3b97e99609ae28aa1ee2eb32">sanitizeFunctionName</a>.</p>

</div>
</div>

### getGlobalIdentifier() {#a9f44684437922cc04a01fcdcc73215d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string GlobalValue::getGlobalIdentifier (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> Linkage, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName)</td>
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

<p>Return the modified name for a global value suitable to be used as the key for a global lookup (e.g.</p>


<p>profile or ThinLTO). The value's original name is <span class="doxyComputerOutput">Name</span> and has linkage of type <span class="doxyComputerOutput">Linkage</span>. The value is defined in module <span class="doxyComputerOutput">FileName</span>.</p>


<p>Declaration at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd3f34fde967eea4eab5a02d7920ef9a">llvm::GlobalIdentifierDelimiter</a>, <a href="#a308b65a044b4f53e31a2026a81c991d2">isLocalLinkage</a> and <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae469e045889685a1288b208a6d85b948">computeGUIDPreservedSymbols</a>.</p>

</div>
</div>

### getGUID() {#a6811428caf500217f319c74e80900c14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue::GUID GlobalValue::getGUID (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> GlobalName)</td>
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

<p>Return a 64-bit global unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> constructed from global value name (i.e.</p>


<p>returned by <a href="#aed99d84162082a52cd08efb7dfe017e4">getGlobalIdentifier()</a>).</p>


<p>Declaration at line 592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a8e89e6935aaf48cde9d60fd12a3dae0f">llvm::sampleprof::MD5Hash</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#a722c677723f1d97d4f91cd8dd3e899ad">llvm::ModuleSummaryIndex::addGlobalValueSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a7d393b2aea23317c9a423e5d99f8e477">addUsedSymbolToPreservedGUID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a49170e37072dd286a1fcf76f2efec373">llvm::buildModuleSummaryIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a1e1c4a4bdaaa3af5a3c988554783bd48">computeAliasSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae469e045889685a1288b208a6d85b948">computeGUIDPreservedSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#aa2ce415bf980facbbfb4eb13a1e9ce54">doesHistoryAllowICP</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa9137eda03e0c2cfd6eebaa55dfdd4cc">anonymous{SampleProfile.cpp}::SampleProfileLoader::findExternalInlineCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#a59c4cec2de3101c3788db6c4d84872dd">findValueInfoForFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobemanager/#aaea75c52e4662f007940b2ebba65e6c0">llvm::PseudoProbeManager::getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobemanager/#a2b57dc92441441093efef4f72613b41b">llvm::PseudoProbeManager::getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#adb6d1f8091dc25c1713b6cbfe642d88b">llvm::ModuleSummaryIndex::getGlobalValueSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#a06ec58fca119b03f6ffea51610851571">llvm::ModuleSummaryIndex::getOrInsertTypeIdSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#ad0c3f445d21c16185ef1df7f3e2f3735">llvm::ModuleSummaryIndex::getOrInsertValueInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a012731cbc58856aff956543ab824eb8d">llvm::sampleprof::getRepInFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#a3c88bbba888dc542d487e2ebbf1dcb7c">llvm::ModuleSummaryIndex::getTypeIdSummary</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/guidtofuncnamemapper/#a0443cc3fdee8b10994d348458d6d9949">anonymous{SampleProfile.cpp}::GUIDToFuncNameMapper::GUIDToFuncNameMapper</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">llvm::FunctionImporter::importFunctions</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#ac623fd2d132c0a19c1b96c76a0821b92">anonymous{LTO.cpp}::InProcessThinBackend::InProcessThinBackend</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#addf7542694401439f2f600b3890c8831">anonymous{WholeProgramDevirt.cpp}::DevirtModule::lookUpFunctionValueInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a873e0df967c1a3a622ee9e25c1a6fa00">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a358b28b8ab641a2a22ed8849a2dff2cf">anonymous{SampleProfile.cpp}::SampleProfileLoader::runOnFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a37994a2b7672d14f55587c8d6311adcf">setLiveRoot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac69630533101ec5ba74953a63082148">llvm::thinLTOInternalizeModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#ad5c772a0b61cb29106af3a4f9ae43d59">anonymous{SampleProfile.cpp}::SampleProfileLoader::tryPromoteAndInlineCandidate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af8b10064b29ab4bb0c85f28342ce72dd">llvm::updateVCallVisibilityInModule</a>.</p>

</div>
</div>

### getLinkOnceLinkage() {#ac00103d63c269693fe360702dd9142d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkageTypes llvm::GlobalValue::getLinkOnceLinkage (bool ODR)</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#aedfa75f0c85c4aa85b257f066fbea57ca5ebf288ceb5bbeb7025564727db6d705">LinkOnceAnyLinkage</a> and <a href="#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">LinkOnceODRLinkage</a>.</p>

</div>
</div>

### getMinUnnamedAddr() {#a6e8300b59be44b0c7913ae50fd5c487e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnnamedAddr llvm::GlobalValue::getMinUnnamedAddr (<a href="#ae8df4be75bfc50b1eadd74e85c25fa45">UnnamedAddr</a> A, <a href="#ae8df4be75bfc50b1eadd74e85c25fa45">UnnamedAddr</a> B)</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ae8df4be75bfc50b1eadd74e85c25fa45a4cc6684df7b4a92b1dec6fce3264fac8">Global</a>, <a href="#ae8df4be75bfc50b1eadd74e85c25fa45a509820290d57f333403f490dde7316f4">Local</a> and <a href="#ae8df4be75bfc50b1eadd74e85c25fa45a6adf97f83acf6453d4a6a4b1070f3754">None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvalue/#ac3f694f930de6dabb72e34e80ef7f98a">llvm::sandboxir::GlobalValue::getMinUnnamedAddr</a>.</p>

</div>
</div>

### getWeakLinkage() {#ab1a929646bd99aa881cff849f40da718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkageTypes llvm::GlobalValue::getWeakLinkage (bool ODR)</td>
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



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">WeakAnyLinkage</a> and <a href="#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">WeakODRLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#a32b95697af129a14bc5ac5adf0465868">thinLTOResolvePrevailingGUID</a>.</p>

</div>
</div>

### isAppendingLinkage() {#a0b09f704d0928e6811660fa3af8f626c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isAppendingLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#aedfa75f0c85c4aa85b257f066fbea57ca96ad6314ba9210b223b93dc3e15baf99">AppendingLinkage</a> and <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>.</p>


<p>Referenced by <a href="#ac90734e1bc3dc440f2db27f4c38a4f43">hasAppendingLinkage</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#a32b95697af129a14bc5ac5adf0465868">thinLTOResolvePrevailingGUID</a>.</p>

</div>
</div>

### isAvailableExternallyLinkage() {#a578061260691a59a9e7b0455fd68359c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isAvailableExternallyLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#aedfa75f0c85c4aa85b257f066fbea57caa67f293befacbbf974525116ccf2ff42">AvailableExternallyLinkage</a> and <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a306df028c5841358ae4f88426c76850a">calculatePrevailingSummary</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#aa300e563274ef893528fb6d22e2cea70">anonymous{StackSafetyAnalysis.cpp}::findCalleeFunctionSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#af00c22607d77d29f2f949fe7a1359e5f">getFirstDefinitionForLinker</a>, <a href="#ae76e0b39c563b63554b4c99a8ad726e4">hasAvailableExternallyLinkage</a>, <a href="#adcb86d621c23938671ad526d3bd1f9bd">isDiscardableIfUnused</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a0dc1071ac8fdde2dc10ba6c7700598f4">llvm::GlobalAlias::isValidLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobemanager/#ad85bb1b041ade18c623e0ea70ab7b1ca">llvm::PseudoProbeManager::profileIsValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a> and <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtindex/#abcd9be7acff38f150936f7bbfe72ac14">anonymous{WholeProgramDevirt.cpp}::DevirtIndex::tryFindVirtualCallTargets</a>.</p>

</div>
</div>

### isCommonLinkage() {#a76d750f65089b2e70a927cf9d275a9d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isCommonLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#aedfa75f0c85c4aa85b257f066fbea57ca08c6a63ca3d9cdb39fb584655bf5c501">CommonLinkage</a> and <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#a8542a1e56f754b563a94e006caac9eea">llvm::JITSymbolFlags::fromSummary</a> and <a href="#ac10ac4576e030b231e1fbb5a8272f01f">hasCommonLinkage</a>.</p>

</div>
</div>

### isDiscardableIfUnused() {#adcb86d621c23938671ad526d3bd1f9bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isDiscardableIfUnused (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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

<p>Whether the definition of this global may be discarded if it is not used in its compilation unit.</p>

<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a578061260691a59a9e7b0455fd68359c">isAvailableExternallyLinkage</a>, <a href="#a4f4d5111c78b4b976e362d12f01ad782">isLinkOnceLinkage</a>, <a href="#a308b65a044b4f53e31a2026a81c991d2">isLocalLinkage</a> and <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abbbd1b6fc4b1028641e564b0e972e18b">llvm::canRenameComdatFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5a50ba4ab5027d4013cf6bc2edf66085">deleteIfDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a1db077f1815950aa2f419be901c429c6">isGOTEquivalentCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/extractgv-cpp/#aecd7db67c15393462f7d55af64644142">makeVisible</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#aba35cb55d089d58ace72978cb0249dc8">optimizeGlobalsInModule</a>.</p>

</div>
</div>

### isExternalLinkage() {#a89a664b58385307fbb24c02e141d864b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isExternalLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">ExternalLinkage</a> and <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a306df028c5841358ae4f88426c76850a">calculatePrevailingSummary</a>, <a href="#aa63851a5f68b64cf93d3f8c4a973f33d">canBenefitFromLocalAlias</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#aa300e563274ef893528fb6d22e2cea70">anonymous{StackSafetyAnalysis.cpp}::findCalleeFunctionSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#a8542a1e56f754b563a94e006caac9eea">llvm::JITSymbolFlags::fromSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/assignguidpass/#a00cd72af35cb6bdeae06467500b531ae">llvm::AssignGUIDPass::getGUID</a>, <a href="#a1847e956a0087fefdb49e2a9583c7d18">hasExternalLinkage</a>, <a href="#a9a2053e12c56247022b52ffd370ec70d">isValidDeclarationLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a0dc1071ac8fdde2dc10ba6c7700598f4">llvm::GlobalAlias::isValidLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalifunc/#a8ec0507d25fa76b3e573cc66288d0929">llvm::GlobalIFunc::isValidLinkage</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#adb4cbf7dec24b6c5a35bec9a0bfdd13f">thinLTOInternalizeAndPromoteGUID</a>.</p>

</div>
</div>

### isExternalWeakLinkage() {#a25e8e3490a28e9178b302b76ae643443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isExternalWeakLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#aedfa75f0c85c4aa85b257f066fbea57caa81fc8db28ac4af45766fbab2e79d466">ExternalWeakLinkage</a> and <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#a8542a1e56f754b563a94e006caac9eea">llvm::JITSymbolFlags::fromSummary</a>, <a href="#a51af265dc931258cdb8ffb37ee6decee">hasExternalWeakLinkage</a>, <a href="#a9a2053e12c56247022b52ffd370ec70d">isValidDeclarationLinkage</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#adb4cbf7dec24b6c5a35bec9a0bfdd13f">thinLTOInternalizeAndPromoteGUID</a>.</p>

</div>
</div>

### isInternalLinkage() {#a9bbb20d12147495c229051feded37cdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isInternalLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">InternalLinkage</a> and <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a0e0ddbf81c5fa1ee764ba3f4bd6ddbf5">CompareValueComplexity</a>, <a href="#a7bc292fc6d075e3ed6e68b0866ec3524">hasInternalLinkage</a> and <a href="#a308b65a044b4f53e31a2026a81c991d2">isLocalLinkage</a>.</p>

</div>
</div>

### isInterposableLinkage() {#aabf6932ed41fc64e17c0030c44eda44e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isInterposableLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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

<p>Whether the definition of this global may be replaced by something non-equivalent at link time.</p>


<p>For example, if a function has weak linkage then the code defining it may be replaced by different code.</p>


<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#aedfa75f0c85c4aa85b257f066fbea57ca96ad6314ba9210b223b93dc3e15baf99">AppendingLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57caa67f293befacbbf974525116ccf2ff42">AvailableExternallyLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57ca08c6a63ca3d9cdb39fb584655bf5c501">CommonLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">ExternalLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57caa81fc8db28ac4af45766fbab2e79d466">ExternalWeakLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">InternalLinkage</a>, <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57ca5ebf288ceb5bbeb7025564727db6d705">LinkOnceAnyLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">LinkOnceODRLinkage</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">PrivateLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">WeakAnyLinkage</a> and <a href="#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">WeakODRLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#a9a7e0e8417f932a2e7ae3eaff2f087e4">llvm::ModuleSummaryIndex::canImportGlobalVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b5d72a4e8c39c8d0ea81cb9c547bc8c">llvm::computeDeadSymbolsAndUpdateIndirectCalls</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a312bc8ef3e9761ec87b3b6d05d6e2420">llvm::Attributor::isInternalizable</a>, <a href="#aa1558e13ceef68db8ea9f4e3b5a64cbd">isInterposable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a6c0ba55113b40b07b869ba9c06db6ca1">OptimizeGlobalAliases</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#a05678176a857aaca26eac45ab65dc3b1">qualifyCalleeCandidates</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a30e276f415c0b092317585c37160f9ce">runAttributorOnFunctions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>.</p>

</div>
</div>

### isLinkOnceAnyLinkage() {#a0dc5c71cdefd415dcc8569ae3f2b7892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isLinkOnceAnyLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a> and <a href="#aedfa75f0c85c4aa85b257f066fbea57ca5ebf288ceb5bbeb7025564727db6d705">LinkOnceAnyLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a306df028c5841358ae4f88426c76850a">calculatePrevailingSummary</a>, <a href="#a3acdc3a8bbb5f15edd761e8aee3e2dfd">hasLinkOnceAnyLinkage</a> and <a href="#a4f4d5111c78b4b976e362d12f01ad782">isLinkOnceLinkage</a>.</p>

</div>
</div>

### isLinkOnceLinkage() {#a4f4d5111c78b4b976e362d12f01ad782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isLinkOnceLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a0dc5c71cdefd415dcc8569ae3f2b7892">isLinkOnceAnyLinkage</a>, <a href="#af4663ee02ad0f28a78539ec85c91bec0">isLinkOnceODRLinkage</a> and <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#aa300e563274ef893528fb6d22e2cea70">anonymous{StackSafetyAnalysis.cpp}::findCalleeFunctionSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#a8542a1e56f754b563a94e006caac9eea">llvm::JITSymbolFlags::fromSummary</a>, <a href="#a091e6599599c4e668373e0feefa92c01">hasLinkOnceLinkage</a>, <a href="#adcb86d621c23938671ad526d3bd1f9bd">isDiscardableIfUnused</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a0dc1071ac8fdde2dc10ba6c7700598f4">llvm::GlobalAlias::isValidLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalifunc/#a8ec0507d25fa76b3e573cc66288d0929">llvm::GlobalIFunc::isValidLinkage</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#a32b95697af129a14bc5ac5adf0465868">thinLTOResolvePrevailingGUID</a>.</p>

</div>
</div>

### isLinkOnceODRLinkage() {#af4663ee02ad0f28a78539ec85c91bec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isLinkOnceODRLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a> and <a href="#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">LinkOnceODRLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a306df028c5841358ae4f88426c76850a">calculatePrevailingSummary</a>, <a href="#ae28d149d03a6ae88267f649bc1dbe42c">hasLinkOnceODRLinkage</a>, <a href="#a4f4d5111c78b4b976e362d12f01ad782">isLinkOnceLinkage</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#a32b95697af129a14bc5ac5adf0465868">thinLTOResolvePrevailingGUID</a>.</p>

</div>
</div>

### isLocalLinkage() {#a308b65a044b4f53e31a2026a81c991d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isLocalLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a9bbb20d12147495c229051feded37cdc">isInternalLinkage</a>, <a href="#a81812ab49218fff82c3a0c378e0a65b0">isPrivateLinkage</a> and <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a306df028c5841358ae4f88426c76850a">calculatePrevailingSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#a2cdcb957bdfaac04b4bb110298fa7625">doImportingForModuleForTest</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#aa300e563274ef893528fb6d22e2cea70">anonymous{StackSafetyAnalysis.cpp}::findCalleeFunctionSummary</a>, <a href="#a9f44684437922cc04a01fcdcc73215d0">getGlobalIdentifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a388b3ce412f145bfac051690e8ef5596">llvm::getPGOFuncName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad9ef6ea647bad0f7fcff3ad4321efb85">llvm::getPGOFuncNameVarName</a>, <a href="#a3ba1af4b9d9faa4a33729bbbecee83d1">hasLocalLinkage</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/indexcallsitecontextgraph/#aa4f54d80f1f0152753a9b60e3f5aea61">anonymous{MemProfContextDisambiguation.cpp}::IndexCallsiteContextGraph::IndexCallsiteContextGraph</a>, <a href="#adcb86d621c23938671ad526d3bd1f9bd">isDiscardableIfUnused</a>, <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp/#afbd8730936ced41a4a321982c143fbda">isValidDLLStorageClassForLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a0dc1071ac8fdde2dc10ba6c7700598f4">llvm::GlobalAlias::isValidLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalifunc/#a8ec0507d25fa76b3e573cc66288d0929">llvm::GlobalIFunc::isValidLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp/#af1cc1d4deb4e05e7fc7c7afb70c5cc5c">isValidVisibilityForLinkage</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="#a687973de03d041e04b50a76d19d4fd36">setLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd3c2c7d03f515419a1785e0a2eb6ea8">llvm::setPGOFuncVisibility</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#a95dfbc76e4eb1f6655f38f2a17e691b3">shouldSkipLocalInAnotherModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#adb4cbf7dec24b6c5a35bec9a0bfdd13f">thinLTOInternalizeAndPromoteGUID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac69630533101ec5ba74953a63082148">llvm::thinLTOInternalizeModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#a32b95697af129a14bc5ac5adf0465868">thinLTOResolvePrevailingGUID</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtindex/#abcd9be7acff38f150936f7bbfe72ac14">anonymous{WholeProgramDevirt.cpp}::DevirtIndex::tryFindVirtualCallTargets</a> and <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtindex/#a0e99a7c09395086976fe39e08dbe36a6">anonymous{WholeProgramDevirt.cpp}::DevirtIndex::trySingleImplDevirt</a>.</p>

</div>
</div>

### isPrivateLinkage() {#a81812ab49218fff82c3a0c378e0a65b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isPrivateLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a> and <a href="#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">PrivateLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a0e0ddbf81c5fa1ee764ba3f4bd6ddbf5">CompareValueComplexity</a>, <a href="#a3ed4c5535997ad77ffee00f92430b576">hasPrivateLinkage</a> and <a href="#a308b65a044b4f53e31a2026a81c991d2">isLocalLinkage</a>.</p>

</div>
</div>

### isValidDeclarationLinkage() {#a9a2053e12c56247022b52ffd370ec70d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isValidDeclarationLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a89a664b58385307fbb24c02e141d864b">isExternalLinkage</a>, <a href="#a25e8e3490a28e9178b302b76ae643443">isExternalWeakLinkage</a> and <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>.</p>


<p>Referenced by <a href="#a334704e7c859bd7c44ca86249a6280cc">hasValidDeclarationLinkage</a>.</p>

</div>
</div>

### isWeakAnyLinkage() {#a0918c134c7b8131fa37df98101cd17db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isWeakAnyLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a> and <a href="#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">WeakAnyLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a306df028c5841358ae4f88426c76850a">calculatePrevailingSummary</a>, <a href="#a61afb04130343acdd861174587400c10">hasWeakAnyLinkage</a> and <a href="#ad48190a47d8af6ce16465cda531725a9">isWeakLinkage</a>.</p>

</div>
</div>

### isWeakForLinker() {#ac291102760c543c8e045e829d57d3341}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isWeakForLinker (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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

<p>Whether the definition of this global may be replaced at link time.</p>


<p>NB: Using this method outside of the code generators is almost always a mistake: when working at the IR level use isInterposable instead as it knows about ODR semantics.</p>


<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#aedfa75f0c85c4aa85b257f066fbea57ca08c6a63ca3d9cdb39fb584655bf5c501">CommonLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57caa81fc8db28ac4af45766fbab2e79d466">ExternalWeakLinkage</a>, <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57ca5ebf288ceb5bbeb7025564727db6d705">LinkOnceAnyLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">LinkOnceODRLinkage</a>, <a href="#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">WeakAnyLinkage</a> and <a href="#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">WeakODRLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#ae36c2a9293b9a50a2870d02f93d7d202">llvm::RecordStreamer::flushSymverDirectives</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ae17d0aeb924fa0611500eb8cb09a70d9">hasUsesToReplace</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#adb4cbf7dec24b6c5a35bec9a0bfdd13f">thinLTOInternalizeAndPromoteGUID</a>.</p>

</div>
</div>

### isWeakLinkage() {#ad48190a47d8af6ce16465cda531725a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isWeakLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#a0918c134c7b8131fa37df98101cd17db">isWeakAnyLinkage</a>, <a href="#a39cdc71d12722bb912f3a299ab5574ab">isWeakODRLinkage</a> and <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#aa300e563274ef893528fb6d22e2cea70">anonymous{StackSafetyAnalysis.cpp}::findCalleeFunctionSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#a8542a1e56f754b563a94e006caac9eea">llvm::JITSymbolFlags::fromSummary</a>, <a href="#aaca0b3e9845b2fa35c965edaabd5c6bc">hasWeakLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a0dc1071ac8fdde2dc10ba6c7700598f4">llvm::GlobalAlias::isValidLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalifunc/#a8ec0507d25fa76b3e573cc66288d0929">llvm::GlobalIFunc::isValidLinkage</a>.</p>

</div>
</div>

### isWeakODRLinkage() {#a39cdc71d12722bb912f3a299ab5574ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalValue::isWeakODRLinkage (<a href="#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage)</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>References <a href="#ad61abcbd08169ff119e819ef0482744d">Linkage</a> and <a href="#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">WeakODRLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a306df028c5841358ae4f88426c76850a">calculatePrevailingSummary</a>, <a href="#ab241086cb8a1e3f7e77fb00c9a8aeb2e">hasWeakODRLinkage</a> and <a href="#ad48190a47d8af6ce16465cda531725a9">isWeakLinkage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Attributes

### GlobalValueSubClassDataBits {#a9a95237a18eb8cdb7f4d1aa99d6120b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::GlobalValue::GlobalValueSubClassDataBits = 15</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>.</p>


<p>Referenced by <a href="#ab4e766c05dc79278ee675263c13c1cb0">setGlobalValueSubClassData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Materialization



<p>Materialization is used to construct functions only as they're needed.</p>


<p>This is useful to reduce memory usage in LLVM or parsing work done by the BitcodeReader to load the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>.</p>


### isMaterializable {#ac010bf63f00b00f321a141448942a697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GlobalValue::isMaterializable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this function's <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> is being lazily streamed in functions from disk or some other source, this method can be used to check to see if the function has been read in yet or not.</p>

<p>Declaration at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a89d2a6c720f05584135f01f20cc3c9ee">anonymous{AsmWriter.cpp}::AssemblyWriter::printIFunc</a>.</p>

</div>
</div>

### materialize {#ac1b5643f40dd3c7b92a548027eb13de0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error GlobalValue::materialize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make sure this <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> is fully read.</p>

<p>Declaration at line 611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="#a739b30c811f1eece61b05320ddf44e5b">getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/module/#a1f304ac10c82c01df336a728197985c1">llvm::Module::materialize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">llvm::FunctionImporter::importFunctions</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">GlobalValue.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
