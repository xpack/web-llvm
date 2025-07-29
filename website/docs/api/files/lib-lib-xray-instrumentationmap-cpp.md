---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/xray/instrumentationmap-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `InstrumentationMap.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/instrumentationmap-h">llvm/XRay/InstrumentationMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/binary-h">llvm/Object/Binary.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">llvm/Object/ELFObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">llvm/Object/ObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/relocationresolver-h">llvm/Object/RelocationResolver.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">llvm/Support/DataExtractor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">llvm/Support/YAMLTraits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;algorithm&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;system_error&gt;
#include &lt;vector&gt;
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae11c7126bb096d02d681c00105c2f6af">RelocMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, uint64_t &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39d3991edccf18f18b801032e9ab89b5">loadObj</a> (StringRef Filename, object::OwningBinary&lt; object::ObjectFile &gt; &amp;ObjFile, InstrumentationMap::SledContainer &amp;Sleds, InstrumentationMap::FunctionAddressMap &amp;FunctionAddresses, InstrumentationMap::FunctionAddressReverseMap &amp;FunctionIds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a740748c1b9bf73c9456e1d823f34c5f2">loadYAML</a> (sys::fs::file_t Fd, size_t FileSize, StringRef Filename, InstrumentationMap::SledContainer &amp;Sleds, InstrumentationMap::FunctionAddressMap &amp;FunctionAddresses, InstrumentationMap::FunctionAddressReverseMap &amp;FunctionIds)</td>
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

## Typedefs

### RelocMap {#ae11c7126bb096d02d681c00105c2f6af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using RelocMap =  DenseMap&lt;uint64_t, uint64_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/instrumentationmap-cpp">InstrumentationMap.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### loadObj() {#a39d3991edccf18f18b801032e9ab89b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error loadObj (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">object::OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &gt; &amp; ObjFile, <a href="/web-llvm/docs/api/classes/llvm/xray/instrumentationmap/#a923dd7374caba5d32a646fb6b6ca3333">InstrumentationMap::SledContainer</a> &amp; Sleds, <a href="/web-llvm/docs/api/classes/llvm/xray/instrumentationmap/#a333606f105ee7aba2513c816d73a455d">InstrumentationMap::FunctionAddressMap</a> &amp; FunctionAddresses, <a href="/web-llvm/docs/api/classes/llvm/xray/instrumentationmap/#a513854f44c6ca8bdc1aac60568e8f9d2">InstrumentationMap::FunctionAddressReverseMap</a> &amp; FunctionIds)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/instrumentationmap-cpp">InstrumentationMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">llvm::Triple::arm</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#adbc826dc76fd535f887e035d1795aa84">llvm::StringRef::bytes_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25ba44ae8e92a80fde434e1ab19994cc">llvm::StringRef::bytes_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/structs/llvm/xray/sledentry/#ac106499ed4c227f4c361a92bd55b460fa624782357b787994e7624c941d945a0b">llvm::xray::SledEntry::CUSTOM_EVENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/structs/llvm/xray/sledentry/#ac106499ed4c227f4c361a92bd55b460fa5d5fa847ba846e56023955fb50c7f803">llvm::xray::SledEntry::ENTRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/structs/llvm/xray/sledentry/#ac106499ed4c227f4c361a92bd55b460faa42b2fb0e720a080e79a92f4ca97d927">llvm::xray::SledEntry::EXIT</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp/#a8900af579239e32944046beb6f37e31a">getAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfrelocationref/#a705b6e9363a0fe644bea482dc295cf83">llvm::object::ELFRelocationRef::getAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/object/owningbinary/#a3f6d33585a43bad491af78cc5c07f605">llvm::object::OwningBinary&lt; T &gt;::getBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a974d2440be47c5644fe899f3ec74a000">llvm::object::getRelocationResolver</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/xray/sledentry/#ac106499ed4c227f4c361a92bd55b460fa155a5209683ae7cbddfffaa817f4f35f">llvm::xray::SledEntry::LOG_ARGS_ENTER</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">llvm::Triple::loongarch64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">llvm::Triple::ppc64le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a3e56be036fa3e00298b097c1bb756643">llvm::object::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08">llvm::Triple::riscv64</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/structs/llvm/xray/sledentry/#ac106499ed4c227f4c361a92bd55b460fa026ba6d3d7dd81197fee244bb8c7fc6d">llvm::xray::SledEntry::TAIL</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/xray/#aa457a825eb8236aa6f36de72e86109ca">llvm::xray::loadInstrumentationMap</a>.</p>

</div>
</div>

### loadYAML() {#a740748c1b9bf73c9456e1d823f34c5f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error loadYAML (<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a8ec705e6a361f51bca14123110ecb75d">sys::fs::file_t</a> Fd, size_t FileSize, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/xray/instrumentationmap/#a923dd7374caba5d32a646fb6b6ca3333">InstrumentationMap::SledContainer</a> &amp; Sleds, <a href="/web-llvm/docs/api/classes/llvm/xray/instrumentationmap/#a333606f105ee7aba2513c816d73a455d">InstrumentationMap::FunctionAddressMap</a> &amp; FunctionAddresses, <a href="/web-llvm/docs/api/classes/llvm/xray/instrumentationmap/#a513854f44c6ca8bdc1aac60568e8f9d2">InstrumentationMap::FunctionAddressReverseMap</a> &amp; FunctionIds)</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/instrumentationmap-cpp">InstrumentationMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a43548658b3d92c080577422f81f38038">llvm::sys::fs::closeFile</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region/#ac1c8135d48119f3ec27065ad285bb400">llvm::sys::fs::mapped_file_region::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region/#a7d087bce12e64c2578f57ca0e1884919a816892378873d0045cdb238bbef751be">llvm::sys::fs::mapped_file_region::readonly</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region/#a1acf074d04e204669531e149b2c6f9c3">llvm::sys::fs::mapped_file_region::size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/xray/#aa457a825eb8236aa6f36de72e86109ca">llvm::xray::loadInstrumentationMap</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
