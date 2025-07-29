---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/offloading
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `offloading` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::offloading { ... }
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/offloading/amdgpu">amdgpu</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offloading/entryty">EntryTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the record of an object that just be registered with the offloading runtime. <a href="/web-llvm/docs/api/structs/llvm/offloading/entryty/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b583147c80ad356eeccb01b64688984">EntryArrayTy</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OffloadEntryKindFlag : uint32_t { <a href="#a7419ce8b8f6793fdec6d80b80d731b57">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offloading entry flags for CUDA / HIP. <a href="#a7419ce8b8f6793fdec6d80b80d731b57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8acaeff0d5377d081e04c0f9c1a0726e">wrapOpenMPBinaries</a> (llvm::Module &amp;M, llvm::ArrayRef&lt; llvm::ArrayRef&lt; char &gt; &gt; Images, EntryArrayTy EntryArray, llvm::StringRef Suffix="", bool Relocatable=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wraps the input device images into the module <span class="doxyComputerOutput">M</span> as global symbols and registers the images with the OpenMP Offloading runtime libomptarget. <a href="#a8acaeff0d5377d081e04c0f9c1a0726e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8476f6b1335517f24e2a9236806f425">wrapCudaBinary</a> (llvm::Module &amp;M, llvm::ArrayRef&lt; char &gt; Images, EntryArrayTy EntryArray, llvm::StringRef Suffix="", bool EmitSurfacesAndTextures=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wraps the input fatbinary image into the module <span class="doxyComputerOutput">M</span> as global symbols and registers the images with the CUDA runtime. <a href="#ae8476f6b1335517f24e2a9236806f425">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad14a169be48a9fd66713e2d0a963223c">wrapHIPBinary</a> (llvm::Module &amp;M, llvm::ArrayRef&lt; char &gt; Images, EntryArrayTy EntryArray, llvm::StringRef Suffix="", bool EmitSurfacesAndTextures=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wraps the input bundled image into the module <span class="doxyComputerOutput">M</span> as global symbols and registers the images with the HIP runtime. <a href="#ad14a169be48a9fd66713e2d0a963223c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6955657cb7867972e6b8f046e9cf5a02">getEntryTy</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the type of the offloading entry we use to store kernels and globals that will be registered with the offloading runtime. <a href="#a6955657cb7867972e6b8f046e9cf5a02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b79b6c874e2b55eb4dda2ae96867f84">emitOffloadingEntry</a> (Module &amp;M, object::OffloadKind Kind, Constant *Addr, StringRef Name, uint64_t Size, uint32_t Flags, uint64_t Data, StringRef SectionName, Constant *AuxAddr=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an offloading section struct used to register this global at runtime. <a href="#a4b79b6c874e2b55eb4dda2ae96867f84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68d20206b060ac3ad19f416ed5a4899b">getOffloadingEntryInitializer</a> (Module &amp;M, object::OffloadKind Kind, Constant *Addr, StringRef Name, uint64_t Size, uint32_t Flags, uint64_t Data, Constant *AuxAddr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a constant struct initializer used to register this global at runtime. <a href="#a68d20206b060ac3ad19f416ed5a4899b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af023297673da795cc027d7aa8fd62817">getOffloadEntryArray</a> (Module &amp;M, StringRef SectionName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a pair of globals used to iterate the array of offloading entries by accessing the section variables provided by the linker. <a href="#af023297673da795cc027d7aa8fd62817">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### EntryArrayTy {#a8b583147c80ad356eeccb01b64688984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::offloading::EntryArrayTy =  std::pair&lt;GlobalVariable *, GlobalVariable *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/offloadwrapper-h">OffloadWrapper.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### OffloadEntryKindFlag {#a7419ce8b8f6793fdec6d80b80d731b57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::offloading::OffloadEntryKindFlag : uint32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offloading entry flags for CUDA / HIP.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OffloadGlobalEntry<a id="a7419ce8b8f6793fdec6d80b80d731b57a923b860456c7e27007bf11d0069cfdb2"></a></td>
<td class="doxyEnumItemDescription">Mark the entry as a global entry (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OffloadGlobalManagedEntry<a id="a7419ce8b8f6793fdec6d80b80d731b57aa0793e58f3eff2e957cb0f21c576bfa8"></a></td>
<td class="doxyEnumItemDescription">Mark the entry as a managed global variable (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OffloadGlobalSurfaceEntry<a id="a7419ce8b8f6793fdec6d80b80d731b57a19c883805ad6071c9922c23720d90676"></a></td>
<td class="doxyEnumItemDescription">Mark the entry as a surface variable (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OffloadGlobalTextureEntry<a id="a7419ce8b8f6793fdec6d80b80d731b57a381cb6a73ee086038196fda5c4d0879a"></a></td>
<td class="doxyEnumItemDescription">Mark the entry as a texture variable (= 0x3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OffloadGlobalExtern<a id="a7419ce8b8f6793fdec6d80b80d731b57ac859aa67b07ccd5fba9df78343e14fed"></a></td>
<td class="doxyEnumItemDescription">Mark the entry as being extern (= 0x1 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OffloadGlobalConstant<a id="a7419ce8b8f6793fdec6d80b80d731b57af71523a48c2d983a6408fbe16cecab94"></a></td>
<td class="doxyEnumItemDescription">Mark the entry as being constant (= 0x1 &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OffloadGlobalNormalized<a id="a7419ce8b8f6793fdec6d80b80d731b57a8db334373b12649f212522b471a4efcc"></a></td>
<td class="doxyEnumItemDescription">Mark the entry as being a normalized surface (= 0x1 &lt;&lt; 5)</td>
</tr>

</table>
</dd>
</dl>


<p>The first three bits indicate the type of entry while the others are a bit field for additional information.</p>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### emitOffloadingEntry() {#a4b79b6c874e2b55eb4dda2ae96867f84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::offloading::emitOffloadingEntry (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a92b4561998310fbcfbeaeb7c449bad6a">object::OffloadKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, uint64_t Size, uint32_t Flags, uint64_t Data, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * AuxAddr=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an offloading section struct used to register this global at runtime.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">M</td>
<td class="doxyParamItemDescription"><p>The module to be used</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>The pointer to the global being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Kind</td>
<td class="doxyParamItemDescription"><p>The offloading language expected to consume this.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>The symbol name associated with the global.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>The size in bytes of the global (0 for functions).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags associated with the entry.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>Extra data storage associated with the entry.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/structs/llvm/sectionname"&gt;SectionName&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The section this entry will be placed at.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AuxAddr</td>
<td class="doxyParamItemDescription"><p>An extra pointer if needed.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a6955657cb7867972e6b8f046e9cf5a02">getEntryTy</a>, <a href="#a68d20206b060ac3ad19f416ed5a4899b">getOffloadingEntryInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9871d348bbc1e85bd1daacb428238707">llvm::Triple::isNVPTX</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a6300d761fd69580d711fad99b934950a">llvm::Triple::isOSBinFormatCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">llvm::GlobalValue::WeakAnyLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#acc290ce16055813d4ee68af4c8023a09">llvm::OpenMPIRBuilder::createOffloadEntriesAndInfoMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ac5805e4c7f00be338494407152cf34aa">llvm::OpenMPIRBuilder::createOffloadEntry</a>.</p>

</div>
</div>

### getEntryTy() {#a6955657cb7867972e6b8f046e9cf5a02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * llvm::offloading::getEntryTy (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the type of the offloading entry we use to store kernels and globals that will be registered with the offloading runtime.</p>

<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a82648246c07eb8a33f628eea28cb988c">llvm::StructType::create</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a87f56db834c58ca630624956ecf6972f">llvm::Type::getInt16Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a75a89f1513d9f9bdcf0366a436ca43b5">llvm::StructType::getTypeByName</a> and <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#aa95d3be8182edf7e68419d38f31dc9de">anonymous{OffloadWrapper.cpp}::createRegisterGlobalsFunction</a>, <a href="#a4b79b6c874e2b55eb4dda2ae96867f84">emitOffloadingEntry</a>, <a href="#af023297673da795cc027d7aa8fd62817">getOffloadEntryArray</a> and <a href="#a68d20206b060ac3ad19f416ed5a4899b">getOffloadingEntryInitializer</a>.</p>

</div>
</div>

### getOffloadEntryArray() {#af023297673da795cc027d7aa8fd62817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; GlobalVariable *, GlobalVariable * &gt; llvm::offloading::getOffloadEntryArray (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a pair of globals used to iterate the array of offloading entries by accessing the section variables provided by the linker.</p>

<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aab730f72aa213d5ecc7d1101efda8811">llvm::appendToCompilerUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero/#abfa1cf8b4348407b167f93bc7c01055f">llvm::ConstantAggregateZero::get</a>, <a href="#a6955657cb7867972e6b8f046e9cf5a02">getEntryTy</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a7eade123587a08e674f2ca72e2443771">llvm::GlobalValue::HiddenVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a6300d761fd69580d711fad99b934950a">llvm::Triple::isOSBinFormatCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#aea6d215256ae43bc9149bf41f2cc7694">llvm::Triple::isOSBinFormatELF</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">llvm::GlobalValue::WeakODRLinkage</a>.</p>

</div>
</div>

### getOffloadingEntryInitializer() {#a68d20206b060ac3ad19f416ed5a4899b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Constant *, GlobalVariable * &gt; llvm::offloading::getOffloadingEntryInitializer (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a92b4561998310fbcfbeaeb7c449bad6a">object::OffloadKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, uint64_t Size, uint32_t Flags, uint64_t Data, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * AuxAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a constant struct initializer used to register this global at runtime.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the constant struct and the global variable holding the symbol name.</p></dd>
</dl>


<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#ae917c72e5b8e15491cd0dbdd44d818f2">llvm::NamedMDNode::addOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a54fcfa620deb80373f489ba2fdad7643">llvm::ConstantStruct::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="#a6955657cb7867972e6b8f046e9cf5a02">getEntryTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a87f56db834c58ca630624956ecf6972f">llvm::Type::getInt16Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a28bf8984fbfb08fd27df435e631e6832">llvm::ConstantExpr::getPointerBitCastOrAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a3edef3fa47c611d3d10606591213e57b">llvm::ConstantDataArray::getString</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45a4cc6684df7b4a92b1dec6fce3264fac8">llvm::GlobalValue::Global</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9871d348bbc1e85bd1daacb428238707">llvm::Triple::isNVPTX</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a4b79b6c874e2b55eb4dda2ae96867f84">emitOffloadingEntry</a>.</p>

</div>
</div>

### wrapCudaBinary() {#ae8476f6b1335517f24e2a9236806f425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::offloading::wrapCudaBinary (<a href="/web-llvm/docs/api/classes/llvm/module">llvm::Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/arrayref">llvm::ArrayRef</a>&lt; char &gt; Images, <a href="#a8b583147c80ad356eeccb01b64688984">EntryArrayTy</a> EntryArray, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Suffix="", bool EmitSurfacesAndTextures=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wraps the input fatbinary image into the module <span class="doxyComputerOutput">M</span> as global symbols and registers the images with the CUDA runtime.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryArray</td>
<td class="doxyParamItemDescription"><p>Optional pair pointing to the <span class="doxyComputerOutput">__start</span> and <span class="doxyComputerOutput">__stop</span> symbols holding the <span class="doxyComputerOutput">__tgt_offload_entry</span> array.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Suffix</td>
<td class="doxyParamItemDescription"><p>An optional suffix appended to the emitted symbols.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EmitSurfacesAndTextures</td>
<td class="doxyParamItemDescription"><p>Whether to emit surface and textures registration code. It defaults to false.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/offloadwrapper-h">OffloadWrapper.h</a>, definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a251d6cd85b676ea4be1e4c2c263494db">anonymous{OffloadWrapper.cpp}::createFatbinDesc</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a274467e5dc615c3f67e96d645c6b9cd3">anonymous{OffloadWrapper.cpp}::createRegisterFatbinFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### wrapHIPBinary() {#ad14a169be48a9fd66713e2d0a963223c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::offloading::wrapHIPBinary (<a href="/web-llvm/docs/api/classes/llvm/module">llvm::Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/arrayref">llvm::ArrayRef</a>&lt; char &gt; Images, <a href="#a8b583147c80ad356eeccb01b64688984">EntryArrayTy</a> EntryArray, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Suffix="", bool EmitSurfacesAndTextures=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wraps the input bundled image into the module <span class="doxyComputerOutput">M</span> as global symbols and registers the images with the HIP runtime.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryArray</td>
<td class="doxyParamItemDescription"><p>Optional pair pointing to the <span class="doxyComputerOutput">__start</span> and <span class="doxyComputerOutput">__stop</span> symbols holding the <span class="doxyComputerOutput">__tgt_offload_entry</span> array.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Suffix</td>
<td class="doxyParamItemDescription"><p>An optional suffix appended to the emitted symbols.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EmitSurfacesAndTextures</td>
<td class="doxyParamItemDescription"><p>Whether to emit surface and textures registration code. It defaults to false.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/offloadwrapper-h">OffloadWrapper.h</a>, definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a251d6cd85b676ea4be1e4c2c263494db">anonymous{OffloadWrapper.cpp}::createFatbinDesc</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a274467e5dc615c3f67e96d645c6b9cd3">anonymous{OffloadWrapper.cpp}::createRegisterFatbinFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### wrapOpenMPBinaries() {#a8acaeff0d5377d081e04c0f9c1a0726e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::offloading::wrapOpenMPBinaries (<a href="/web-llvm/docs/api/classes/llvm/module">llvm::Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/arrayref">llvm::ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">llvm::ArrayRef</a>&lt; char &gt; &gt; Images, <a href="#a8b583147c80ad356eeccb01b64688984">EntryArrayTy</a> EntryArray, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Suffix="", bool Relocatable=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wraps the input device images into the module <span class="doxyComputerOutput">M</span> as global symbols and registers the images with the OpenMP Offloading runtime libomptarget.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryArray</td>
<td class="doxyParamItemDescription"><p>Optional pair pointing to the <span class="doxyComputerOutput">__start</span> and <span class="doxyComputerOutput">__stop</span> symbols holding the <span class="doxyComputerOutput">__tgt_offload_entry</span> array.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Suffix</td>
<td class="doxyParamItemDescription"><p>An optional suffix appended to the emitted symbols.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Relocatable</td>
<td class="doxyParamItemDescription"><p>Indicate if we need to change the offloading section to create a relocatable object.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/offloadwrapper-h">OffloadWrapper.h</a>, definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a6f467de3ca984f069ee86b9558388294">anonymous{OffloadWrapper.cpp}::createBinDesc</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#afb5a26693a2aa4ccb54923bf6a6e86d6">anonymous{OffloadWrapper.cpp}::createRegisterFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/offloadwrapper-h">OffloadWrapper.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
