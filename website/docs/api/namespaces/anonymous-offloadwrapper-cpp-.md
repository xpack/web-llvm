---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-offloadwrapper-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{OffloadWrapper.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{OffloadWrapper.cpp} { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a106719002236502dad13854dfc2e86cd">getSizeTTy</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ba7541c9160f54941d8b6029ec4d2ae">getDeviceImageTy</a> (Module &amp;M)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4020d9f897807c61a6c30e270ef7e1c">getDeviceImagePtrTy</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a604c924e11ca5df4475086acc8db0f4e">getBinDescTy</a> (Module &amp;M)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2b810a52c1fec67f50c9c4af0d60abe">getBinDescPtrTy</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f467de3ca984f069ee86b9558388294">createBinDesc</a> (Module &amp;M, ArrayRef&lt; ArrayRef&lt; char &gt; &gt; Bufs, EntryArrayTy EntryArray, StringRef Suffix, bool Relocatable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates binary descriptor for the given device images. <a href="#a6f467de3ca984f069ee86b9558388294">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a483af07ad9cee019751803fda2e04d1e">createUnregisterFunction</a> (Module &amp;M, GlobalVariable *BinDesc, StringRef Suffix)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb5a26693a2aa4ccb54923bf6a6e86d6">createRegisterFunction</a> (Module &amp;M, GlobalVariable *BinDesc, StringRef Suffix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad046f69ab8abe8d2605589e6daf42612">getFatbinWrapperTy</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a251d6cd85b676ea4be1e4c2c263494db">createFatbinDesc</a> (Module &amp;M, ArrayRef&lt; char &gt; Image, bool IsHIP, StringRef Suffix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Embed the image <span class="doxyComputerOutput">Image</span> into the module <span class="doxyComputerOutput">M</span> so it can be found by the runtime. <a href="#a251d6cd85b676ea4be1e4c2c263494db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa95d3be8182edf7e68419d38f31dc9de">createRegisterGlobalsFunction</a> (Module &amp;M, bool IsHIP, EntryArrayTy EntryArray, StringRef Suffix, bool EmitSurfacesAndTextures)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the register globals function. <a href="#aa95d3be8182edf7e68419d38f31dc9de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a274467e5dc615c3f67e96d645c6b9cd3">createRegisterFatbinFunction</a> (Module &amp;M, GlobalVariable *FatbinDesc, bool IsHIP, EntryArrayTy EntryArray, StringRef Suffix, bool EmitSurfacesAndTextures)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e9e518ea02ebd547acc7acc17a38781">CudaFatMagic</a> = 0x466243b1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Magic number that begins the section containing the CUDA fatbinary. <a href="#a7e9e518ea02ebd547acc7acc17a38781">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b61d68c10cab55023942658e18b3ac4">HIPFatMagic</a> = 0x48495046</td>
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


<div class="doxySectionDef">

## Functions

### createBinDesc() {#a6f467de3ca984f069ee86b9558388294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * anonymous{OffloadWrapper.cpp}::createBinDesc (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt; &gt; Bufs, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a8b583147c80ad356eeccb01b64688984">EntryArrayTy</a> EntryArray, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Suffix, bool Relocatable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates binary descriptor for the given device images.</p>


<p>Binary descriptor is an object that is passed to the offloading runtime at program startup and it describes all device images available in the executable or shared library. It is defined as follows</p>


<p><b>attribute</b>((visibility("hidden"))) extern <b>tgt_offload_entry *__start_omp_offloading_entries; __attribute</b>((visibility("hidden"))) extern __tgt_offload_entry *__stop_omp_offloading_entries;</p>


<p>static const char Image0[] = { &lt;Bufs.front() contents&gt; }; ... static const char ImageN[] = { &lt;Bufs.back() contents&gt; };</p>


<p>static const __tgt_device_image Images[] = { { Image0, /*ImageStart*‍/ Image0 + sizeof(Image0), /*ImageEnd*‍/ __start_omp_offloading_entries, /*EntriesBegin*‍/ __stop_omp_offloading_entries /*EntriesEnd*‍/ }, ... { ImageN, /*ImageStart*‍/ ImageN + sizeof(ImageN), /*ImageEnd*‍/ __start_omp_offloading_entries, /*EntriesBegin*‍/ __stop_omp_offloading_entries /*EntriesEnd*‍/ } };</p>


<p>static const __tgt_bin_desc BinDesc = { sizeof(Images) / sizeof(Images[0]), /*NumDeviceImages*‍/ Images, /*DeviceImages*‍/ __start_omp_offloading_entries, /*HostEntriesBegin*‍/ __stop_omp_offloading_entries /*HostEntriesEnd*‍/ };</p>


<p>Global variable that represents BinDesc is returned.</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantarray/#a0900dacdc7ad8e3ea0cc92993c7fd422">llvm::ConstantArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a4a1000e5803e731e9dcc572042a98a0b">llvm::ConstantDataArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a54fcfa620deb80373f489ba2fdad7643">llvm::ConstantStruct::get</a>, <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#a084b7cfd2acc52fcfd2121bad6608ba8">llvm::object::OffloadBinary::getAlignment</a>, <a href="#a604c924e11ca5df4475086acc8db0f4e">getBinDescTy</a>, <a href="#a8ba7541c9160f54941d8b6029ec4d2ae">getDeviceImageTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae4d4490a35a575d97166684fb15f8662">llvm::ConstantExpr::getGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="#a106719002236502dad13854dfc2e86cd">getSizeTTy</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45a4cc6684df7b4a92b1dec6fce3264fac8">llvm::GlobalValue::Global</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a00941e59a16ad6eb14e905557a612501">llvm::identify_magic</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa91e1aaaa67b1f5232dbea39497ef9250">llvm::file_magic::offload_binary</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a8acaeff0d5377d081e04c0f9c1a0726e">llvm::offloading::wrapOpenMPBinaries</a>.</p>

</div>
</div>

### createFatbinDesc() {#a251d6cd85b676ea4be1e4c2c263494db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * anonymous{OffloadWrapper.cpp}::createFatbinDesc (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt; Image, bool IsHIP, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Suffix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Embed the image <span class="doxyComputerOutput">Image</span> into the module <span class="doxyComputerOutput">M</span> so it can be found by the runtime.</p>

<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a7e9e518ea02ebd547acc7acc17a38781">CudaFatMagic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a4a1000e5803e731e9dcc572042a98a0b">llvm::ConstantDataArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a54fcfa620deb80373f489ba2fdad7643">llvm::ConstantStruct::get</a>, <a href="#ad046f69ab8abe8d2605589e6daf42612">getFatbinWrapperTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a28bf8984fbfb08fd27df435e631e6832">llvm::ConstantExpr::getPointerBitCastOrAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="#a4b61d68c10cab55023942658e18b3ac4">HIPFatMagic</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#aa6a7d5d218ef0d2334fe24eaf997bbb6">llvm::Triple::isMacOSX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#ae8476f6b1335517f24e2a9236806f425">llvm::offloading::wrapCudaBinary</a> and <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#ad14a169be48a9fd66713e2d0a963223c">llvm::offloading::wrapHIPBinary</a>.</p>

</div>
</div>

### createRegisterFatbinFunction() {#a274467e5dc615c3f67e96d645c6b9cd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{OffloadWrapper.cpp}::createRegisterFatbinFunction (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * FatbinDesc, bool IsHIP, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a8b583147c80ad356eeccb01b64688984">EntryArrayTy</a> EntryArray, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Suffix, bool EmitSurfacesAndTextures)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac030f6d03b674c2d132fd54fb60c9f26">llvm::appendToGlobalCtors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3313ae2d314fb689cebdaf062d86eec5">llvm::IRBuilderBase::CreateAlignedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="#aa95d3be8182edf7e68419d38f31dc9de">createRegisterGlobalsFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa6536556982b7e6e2e5884e471f3ce6b">llvm::IRBuilderBase::CreateRetVoid</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a28bf8984fbfb08fd27df435e631e6832">llvm::ConstantExpr::getPointerBitCastOrAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#ae8476f6b1335517f24e2a9236806f425">llvm::offloading::wrapCudaBinary</a> and <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#ad14a169be48a9fd66713e2d0a963223c">llvm::offloading::wrapHIPBinary</a>.</p>

</div>
</div>

### createRegisterFunction() {#afb5a26693a2aa4ccb54923bf6a6e86d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{OffloadWrapper.cpp}::createRegisterFunction (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * BinDesc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Suffix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac030f6d03b674c2d132fd54fb60c9f26">llvm::appendToGlobalCtors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa6536556982b7e6e2e5884e471f3ce6b">llvm::IRBuilderBase::CreateRetVoid</a>, <a href="#a483af07ad9cee019751803fda2e04d1e">createUnregisterFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="#ab2b810a52c1fec67f50c9c4af0d60abe">getBinDescPtrTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a8acaeff0d5377d081e04c0f9c1a0726e">llvm::offloading::wrapOpenMPBinaries</a>.</p>

</div>
</div>

### createRegisterGlobalsFunction() {#aa95d3be8182edf7e68419d38f31dc9de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * anonymous{OffloadWrapper.cpp}::createRegisterGlobalsFunction (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, bool IsHIP, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a8b583147c80ad356eeccb01b64688984">EntryArrayTy</a> EntryArray, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Suffix, bool EmitSurfacesAndTextures)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the register globals function.</p>


<p>We will iterate all of the offloading entries stored at the begin / end symbols and register them according to their type. This creates the following function in IR:</p>


<p>extern struct __tgt_offload_entry __start_cuda_offloading_entries; extern struct __tgt_offload_entry __stop_cuda_offloading_entries;</p>


<p>extern void __cudaRegisterFunction(void **, void *, void *, void *, int,
                                   void *, void *, void *, void *, int *); extern void __cudaRegisterVar(void **, void *, void *, void *, int32_t,
                              int64_t, int32_t, int32_t);</p>


<p>void __cudaRegisterTest(void **fatbinHandle) { for (struct __tgt_offload_entry *entry = &amp;__start_cuda_offloading_entries; entry != &amp;__stop_cuda_offloading_entries; ++entry) { if (entry-&gt;Kind != OFK_CUDA) continue</p>


<p>if (!entry-&gt;Size) __cudaRegisterFunction(fatbinHandle, entry-&gt;addr, entry-&gt;name, entry-&gt;name, -1, 0, 0, 0, 0, 0); else __cudaRegisterVar(fatbinHandle, entry-&gt;addr, entry-&gt;name, entry-&gt;name, 0, entry-&gt;size, 0, 0); } }</p>


<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0f9858d25f3972978a0c1fc3aaecd9b9a4cc26eca46c3ce40194e36e7a7a71e6a">ConstantBit</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#abab736a0141f903dc32a6f48828ad908">llvm::IRBuilderBase::CreateBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a972c30f044db799668bdcace5544edeb">llvm::IRBuilderBase::CreateCondBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8c75539a39f167f352b37ccdd788a7e4">llvm::IRBuilderBase::CreateICmpEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64b6c97b8faad5ec83f37d906fca7bc4">llvm::IRBuilderBase::CreateInBoundsGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a876fb556ecea804faa2cd8ad1e498ec3">llvm::IRBuilderBase::CreatePHI</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa6536556982b7e6e2e5884e471f3ce6b">llvm::IRBuilderBase::CreateRetVoid</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8b123015de85b2f41b0deda2aeaad9d3">llvm::IRBuilderBase::CreateSwitch</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af3a2b03b115846b5339469ce1e603976a498ab78ee0b25ce33c83714c1a453831">llvm::Extern</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a6955657cb7867972e6b8f046e9cf5a02">llvm::offloading::getEntryTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a0fbdc8f9ebcc506b52a9f5c82feb363e">llvm::ConstantExpr::getInBoundsGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a87f56db834c58ca630624956ecf6972f">llvm::Type::getInt16Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="#a106719002236502dad13854dfc2e86cd">getSizeTTy</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a7419ce8b8f6793fdec6d80b80d731b57af71523a48c2d983a6408fbe16cecab94">llvm::offloading::OffloadGlobalConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a7419ce8b8f6793fdec6d80b80d731b57a923b860456c7e27007bf11d0069cfdb2">llvm::offloading::OffloadGlobalEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a7419ce8b8f6793fdec6d80b80d731b57ac859aa67b07ccd5fba9df78343e14fed">llvm::offloading::OffloadGlobalExtern</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a7419ce8b8f6793fdec6d80b80d731b57aa0793e58f3eff2e957cb0f21c576bfa8">llvm::offloading::OffloadGlobalManagedEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a7419ce8b8f6793fdec6d80b80d731b57a8db334373b12649f212522b471a4efcc">llvm::offloading::OffloadGlobalNormalized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a7419ce8b8f6793fdec6d80b80d731b57a19c883805ad6071c9922c23720d90676">llvm::offloading::OffloadGlobalSurfaceEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a7419ce8b8f6793fdec6d80b80d731b57a381cb6a73ee086038196fda5c4d0879a">llvm::offloading::OffloadGlobalTextureEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a92b4561998310fbcfbeaeb7c449bad6aa956a23aa136219b3b701185881e3b09d">llvm::object::OFK_Cuda</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a92b4561998310fbcfbeaeb7c449bad6aac363f75245823860bf5b7218b815adc6">llvm::object::OFK_HIP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a274467e5dc615c3f67e96d645c6b9cd3">createRegisterFatbinFunction</a>.</p>

</div>
</div>

### createUnregisterFunction() {#a483af07ad9cee019751803fda2e04d1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * anonymous{OffloadWrapper.cpp}::createUnregisterFunction (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * BinDesc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Suffix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa6536556982b7e6e2e5884e471f3ce6b">llvm::IRBuilderBase::CreateRetVoid</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="#ab2b810a52c1fec67f50c9c4af0d60abe">getBinDescPtrTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>.</p>


<p>Referenced by <a href="#afb5a26693a2aa4ccb54923bf6a6e86d6">createRegisterFunction</a>.</p>

</div>
</div>

### getBinDescPtrTy() {#ab2b810a52c1fec67f50c9c4af0d60abe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType * anonymous{OffloadWrapper.cpp}::getBinDescPtrTy (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>.</p>


<p>Referenced by <a href="#afb5a26693a2aa4ccb54923bf6a6e86d6">createRegisterFunction</a> and <a href="#a483af07ad9cee019751803fda2e04d1e">createUnregisterFunction</a>.</p>

</div>
</div>

### getBinDescTy() {#a604c924e11ca5df4475086acc8db0f4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * anonymous{OffloadWrapper.cpp}::getBinDescTy (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a82648246c07eb8a33f628eea28cb988c">llvm::StructType::create</a>, <a href="#ad4020d9f897807c61a6c30e270ef7e1c">getDeviceImagePtrTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a75a89f1513d9f9bdcf0366a436ca43b5">llvm::StructType::getTypeByName</a> and <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>.</p>


<p>Referenced by <a href="#a6f467de3ca984f069ee86b9558388294">createBinDesc</a>.</p>

</div>
</div>

### getDeviceImagePtrTy() {#ad4020d9f897807c61a6c30e270ef7e1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType * anonymous{OffloadWrapper.cpp}::getDeviceImagePtrTy (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>.</p>


<p>Referenced by <a href="#a604c924e11ca5df4475086acc8db0f4e">getBinDescTy</a>.</p>

</div>
</div>

### getDeviceImageTy() {#a8ba7541c9160f54941d8b6029ec4d2ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * anonymous{OffloadWrapper.cpp}::getDeviceImageTy (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a82648246c07eb8a33f628eea28cb988c">llvm::StructType::create</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a75a89f1513d9f9bdcf0366a436ca43b5">llvm::StructType::getTypeByName</a> and <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>.</p>


<p>Referenced by <a href="#a6f467de3ca984f069ee86b9558388294">createBinDesc</a>.</p>

</div>
</div>

### getFatbinWrapperTy() {#ad046f69ab8abe8d2605589e6daf42612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * anonymous{OffloadWrapper.cpp}::getFatbinWrapperTy (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a82648246c07eb8a33f628eea28cb988c">llvm::StructType::create</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a75a89f1513d9f9bdcf0366a436ca43b5">llvm::StructType::getTypeByName</a> and <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>.</p>


<p>Referenced by <a href="#a251d6cd85b676ea4be1e4c2c263494db">createFatbinDesc</a>.</p>

</div>
</div>

### getSizeTTy() {#a106719002236502dad13854dfc2e86cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType * anonymous{OffloadWrapper.cpp}::getSizeTTy (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>Referenced by <a href="#a6f467de3ca984f069ee86b9558388294">createBinDesc</a> and <a href="#aa95d3be8182edf7e68419d38f31dc9de">createRegisterGlobalsFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CudaFatMagic {#a7e9e518ea02ebd547acc7acc17a38781}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{OffloadWrapper.cpp}::CudaFatMagic = 0x466243b1</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Magic number that begins the section containing the CUDA fatbinary.</p>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>Referenced by <a href="#a251d6cd85b676ea4be1e4c2c263494db">createFatbinDesc</a>.</p>

</div>
</div>

### HIPFatMagic {#a4b61d68c10cab55023942658e18b3ac4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{OffloadWrapper.cpp}::HIPFatMagic = 0x48495046</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a>.</p>


<p>Referenced by <a href="#a251d6cd85b676ea4be1e4c2c263494db">createFatbinDesc</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/offloadwrapper-cpp">OffloadWrapper.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
