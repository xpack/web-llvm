---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/machochainedfixupentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachOChainedFixupEntry` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::MachOChainedFixupEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">llvm/Object/MachO.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry">MachOAbstractFixupEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry">MachOAbstractFixupEntry</a> is an abstract class representing a fixup in a MH_DYLDLINK file. <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FixupKind { <a href="#afadeb10208c1faecf95dd159ff9a4673">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f2f9b655a6e370dd8792b2eeede2ea1">MachOChainedFixupEntry</a> (Error *Err, const MachOObjectFile *O, bool Parse)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35b61c6d12c2d79861b7f5d83765072b">operator==</a> (const MachOChainedFixupEntry &amp;) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa65788f928d958aa0b81e848637a7a9a">isBind</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4917c502d60113625e6bfd3c579bb451">isRebase</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ac5316af2beb36b1eee67c09c7448f8">moveNext</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9238134129c8aed37a5a4274fdda8676">moveToFirst</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6babc84320fb3f2fa66c109c58c8b1f2">moveToEnd</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89969ce9a731632dbd229510dd6e67b9">findNextPageWithFixups</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/object/chainedfixuptarget">ChainedFixupTarget</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61e8396dd3dbfd560e397cf74f84945f">FixupTargets</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/object/chainedfixupssegment">ChainedFixupsSegment</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f442a22e8a09b27a9836fd0868bc08b">Segments</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e93be08be47f9baac2f6d2a6e07a489">SegmentData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afadeb10208c1faecf95dd159ff9a4673">FixupKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f39220cb4f7c95ecb2c77f693a4fb7f">Kind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ecf77d72cd3ad8069829e64405bfdbf">InfoSegIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae31b2de3fd83bab077bcc26af3ba1ad8">PageIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3adb1dc368782de75453409745691889">PageOffset</a> = 0</td>
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


<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### FixupKind {#afadeb10208c1faecf95dd159ff9a4673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::object::MachOChainedFixupEntry::FixupKind </td>
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
<td class="doxyEnumItemName">Bind<a id="afadeb10208c1faecf95dd159ff9a4673a0b172674284d79079624051d2ae11581"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Rebase<a id="afadeb10208c1faecf95dd159ff9a4673a69f7867d1fd6a74b2b64b9dcd8ccd8d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachOChainedFixupEntry() {#a5f2f9b655a6e370dd8792b2eeede2ea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOChainedFixupEntry::MachOChainedFixupEntry (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> * O, bool Parse)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3317 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#ad960b227c861de4dec3ae4e952502359">llvm::object::MachOAbstractFixupEntry::E</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#a7a5c724a4788135ad66edb2be0a81927">llvm::object::MachOAbstractFixupEntry::MachOAbstractFixupEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#aee04f68132b24f954142920e9907d47f">llvm::object::MachOAbstractFixupEntry::O</a>.</p>


<p>Referenced by <a href="#a35b61c6d12c2d79861b7f5d83765072b">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#a35b61c6d12c2d79861b7f5d83765072b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOChainedFixupEntry::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry">MachOChainedFixupEntry</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3469 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#ab10af10cfaadf6fa5d5e85b0d2047cae">llvm::object::MachOAbstractFixupEntry::Done</a>, <a href="#a5f2f9b655a6e370dd8792b2eeede2ea1">MachOChainedFixupEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isBind() {#aa65788f928d958aa0b81e848637a7a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::MachOChainedFixupEntry::isBind ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Reference <a href="#afadeb10208c1faecf95dd159ff9a4673a0b172674284d79079624051d2ae11581">Bind</a>.</p>

</div>
</div>

### isRebase() {#a4917c502d60113625e6bfd3c579bb451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::MachOChainedFixupEntry::isRebase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Reference <a href="#afadeb10208c1faecf95dd159ff9a4673a69f7867d1fd6a74b2b64b9dcd8ccd8d6">Rebase</a>.</p>

</div>
</div>

### moveNext() {#a1ac5316af2beb36b1eee67c09c7448f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOChainedFixupEntry::moveNext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3379 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#ae1b832cfb5038b187d63082022ccefa8">llvm::object::MachOAbstractFixupEntry::Addend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afadeb10208c1faecf95dd159ff9a4673a0b172674284d79079624051d2ae11581">Bind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a842301af3a51cf544c9b80ccb1eac620a56038a653e5a6de1c74a26a66dd99b2f">llvm::MachO::BIND_SYMBOL_FLAGS_WEAK_IMPORT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#ab10af10cfaadf6fa5d5e85b0d2047cae">llvm::object::MachOAbstractFixupEntry::Done</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a92856f89523a9e0a2ec7007bca2621e4aec4d983a032ce5b7dc83429fdbf2b061">llvm::MachO::DYLD_CHAINED_PTR_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a92856f89523a9e0a2ec7007bca2621e4ae04334203c466740661f7629ba0a1020">llvm::MachO::DYLD_CHAINED_PTR_64_OFFSET</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#ad960b227c861de4dec3ae4e952502359">llvm::object::MachOAbstractFixupEntry::E</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#a0c19099c69732495167457fd55a00d7b">llvm::object::MachOAbstractFixupEntry::Flags</a>, <a href="/web-llvm/docs/api/structs/llvm/object/chainedfixupssegment/#a19ad985610beb118307ece50312b8f75">llvm::object::ChainedFixupsSegment::Header</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="#a6babc84320fb3f2fa66c109c58c8b1f2">moveToEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#aee04f68132b24f954142920e9907d47f">llvm::object::MachOAbstractFixupEntry::O</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#aecf255fb43542c54c0615e0c3374de6e">llvm::object::MachOAbstractFixupEntry::Ordinal</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-starts-in-segment/#a44631874833d837802973fbd569cd621">llvm::MachO::dyld_chained_starts_in_segment::page_size</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-starts-in-segment/#a73c781bc645eed51feca91b4177e321e">llvm::MachO::dyld_chained_starts_in_segment::pointer_format</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#abc8f4c6150a51ad161e5888bc62029aa">llvm::object::MachOAbstractFixupEntry::PointerValue</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#a1004e8fd48db72eb421cbdbbb12d6b6a">llvm::object::MachOAbstractFixupEntry::RawValue</a>, <a href="#afadeb10208c1faecf95dd159ff9a4673a69f7867d1fd6a74b2b64b9dcd8ccd8d6">Rebase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2554a96c67bdd7d0a62855a844ec55b0a92b09c7c48c520c3c55e497875da437c">llvm::Right</a>, <a href="/web-llvm/docs/api/structs/llvm/object/chainedfixupssegment/#a13627e086bf022bcbe1646db04e10213">llvm::object::ChainedFixupsSegment::SegIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#abd024ce2eebd7b07cc4c659c8112be13">llvm::object::MachOAbstractFixupEntry::SegmentIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#a4bd8b7d16088e28f13ffaadd0a3d92b2">llvm::object::MachOAbstractFixupEntry::SegmentOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ad0e418047a3e04c4fd1fb83325b571ae">llvm::sys::swapByteOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#a65b46c8e7ab964fb57866644a2c46a56">llvm::object::MachOAbstractFixupEntry::SymbolName</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#a83a82529e6317d5daafd32d4a0416818">llvm::object::MachOAbstractFixupEntry::textAddress</a>.</p>


<p>Referenced by <a href="#a9238134129c8aed37a5a4274fdda8676">moveToFirst</a>.</p>

</div>
</div>

### moveToEnd() {#a6babc84320fb3f2fa66c109c58c8b1f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOChainedFixupEntry::moveToEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3375 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#ae155e3bbdfe979091b05ce2ab8c6c98c">llvm::object::MachOAbstractFixupEntry::moveToEnd</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ab5a90ce0e16d404e8c90801cf2d4ee27">llvm::object::MachOObjectFile::fixupTable</a> and <a href="#a1ac5316af2beb36b1eee67c09c7448f8">moveNext</a>.</p>

</div>
</div>

### moveToFirst() {#a9238134129c8aed37a5a4274fdda8676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOChainedFixupEntry::moveToFirst ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3361 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#ab10af10cfaadf6fa5d5e85b0d2047cae">llvm::object::MachOAbstractFixupEntry::Done</a>, <a href="#a1ac5316af2beb36b1eee67c09c7448f8">moveNext</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#abb42d8a720b462a7bbd69c29c46deba3">llvm::object::MachOAbstractFixupEntry::moveToFirst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### findNextPageWithFixups() {#a89969ce9a731632dbd229510dd6e67b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOChainedFixupEntry::findNextPageWithFixups ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3340 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FixupTargets {#a61e8396dd3dbfd560e397cf74f84945f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ChainedFixupTarget&gt; llvm::object::MachOChainedFixupEntry::FixupTargets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### InfoSegIndex {#a5ecf77d72cd3ad8069829e64405bfdbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::MachOChainedFixupEntry::InfoSegIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### Kind {#a7f39220cb4f7c95ecb2c77f693a4fb7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixupKind llvm::object::MachOChainedFixupEntry::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### PageIndex {#ae31b2de3fd83bab077bcc26af3ba1ad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::MachOChainedFixupEntry::PageIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### PageOffset {#a3adb1dc368782de75453409745691889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::MachOChainedFixupEntry::PageOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### SegmentData {#a4e93be08be47f9baac2f6d2a6e07a489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint8_t&gt; llvm::object::MachOChainedFixupEntry::SegmentData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### Segments {#a6f442a22e8a09b27a9836fd0868bc08b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ChainedFixupsSegment&gt; llvm::object::MachOChainedFixupEntry::Segments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
