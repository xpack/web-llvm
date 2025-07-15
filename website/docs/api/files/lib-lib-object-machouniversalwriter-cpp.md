---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/object/machouniversalwriter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MachOUniversalWriter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversalwriter-h">llvm/Object/MachOUniversalWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">llvm/Object/Archive.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/binary-h">llvm/Object/Binary.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">llvm/Object/IRObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">llvm/Object/MachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">llvm/Object/MachOUniversal.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">llvm/Support/MemoryBufferRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/swapbyteorder-h">llvm/Support/SwapByteOrder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/fatarchtraits">FatArchTraits&lt;FatArchTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/fatarchtraits-c23821ae45ece51858be9b584426b8f1">FatArchTraits&lt;MachO::fat_arch&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/fatarchtraits-049c1ca07a2a4b8e09fbdc54618ff98d">FatArchTraits&lt;MachO::fat_arch_64&gt;</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bf634bff154a80584a034eeff03e8ec">MachoCPUTy</a> = std::pair&lt; uint32_t, uint32_t &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf1bd036dc392e17aec8733d9a180e0">calculateFileAlignment</a> (const MachOObjectFile &amp;O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4f2517d263c6c7cee04ecdcd17a4d7c">calculateAlignment</a> (const MachOObjectFile &amp;ObjectFile)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="#a3bf634bff154a80584a034eeff03e8ec">MachoCPUTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a447fb438fbe4827b7be5fd0a496fe297">getMachoCPUFromTriple</a> (Triple TT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="#a3bf634bff154a80584a034eeff03e8ec">MachoCPUTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add388c33f2c700c6e3deb6056e996097">getMachoCPUFromTriple</a> (StringRef TT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a3bf634bff154a80584a034eeff03e8ec">MachoCPUTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46ef10928db52a0401fc0af59f1a2635">getMachoCPUFromObjectFile</a> (const MachOObjectFile &amp;O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FatArchTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac65c36245c627cb9fb40879101d952a8">buildFatArchList</a> (ArrayRef&lt; Slice &gt; Slices) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; FatArchTy, 2 &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FatArchTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9f26efe564d8f7f1afb5f3033156d58d">writeUniversalArchsToStream</a> (MachO::fat_header FatHeader, ArrayRef&lt; Slice &gt; Slices, raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ecfcee41769620d62e904e7f142499">FatArchTraits&lt; MachO::fat_arch &gt;::StructName</a> = "fat_arch"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6714ecab90ae29c500b77df510c3783f">FatArchTraits&lt; MachO::fat_arch_64 &gt;::StructName</a> = "fat_arch_64"</td>
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

### MachoCPUTy {#a3bf634bff154a80584a034eeff03e8ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MachoCPUTy =  std::pair&lt;uint32_t, uint32_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp">MachOUniversalWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### buildFatArchList() {#ac65c36245c627cb9fb40879101d952a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FatArchTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SmallVector&lt; FatArchTy, 2 &gt; &gt; buildFatArchList (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/slice">Slice</a> &gt; Slices)</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp">MachOUniversalWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/structs/fatarchtraits/#ad69f57f404d568eb0658e4a78d9ba1de">FatArchTraits&lt; FatArchTy &gt;::BitCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/fatarchtraits/#a7c46f70a6bbc9ca4ffb711c5b80a73cb">FatArchTraits&lt; FatArchTy &gt;::OffsetLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/structs/fatarchtraits/#a1846201e5f0baa350694107eb99ea84c">FatArchTraits&lt; FatArchTy &gt;::StructName</a>.</p>


<p>Referenced by <a href="#a9f26efe564d8f7f1afb5f3033156d58d">writeUniversalArchsToStream</a>.</p>

</div>
</div>

### calculateAlignment() {#ad4f2517d263c6c7cee04ecdcd17a4d7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t calculateAlignment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; ObjectFile)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp">MachOUniversalWriter.cpp</a>.</p>


<p>References <a href="#a0cf1bd036dc392e17aec8733d9a180e0">calculateFileAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47ae4da455e762f086662789406e1f085e0">llvm::MachO::CPU_TYPE_ARM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a33fddb0190d728c25e266a22d64bd7ad">llvm::MachO::CPU_TYPE_ARM64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a03cac236584f93f35c9ff89f2d65b716">llvm::MachO::CPU_TYPE_ARM64_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47aa9f8e9712ff2848d650f3c5d8c43c2f8">llvm::MachO::CPU_TYPE_I386</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a630a338da04bb807aac2b41f8fe4e6e7">llvm::MachO::CPU_TYPE_POWERPC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a6f5e12941e8587f9157b470d297fa451">llvm::MachO::CPU_TYPE_POWERPC64</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a633855cb5719de40d81669897cc571c8">llvm::MachO::CPU_TYPE_X86_64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/slice/#ae913fa0b576bcb9513a06818a5208f17">llvm::object::Slice::Slice</a>.</p>

</div>
</div>

### calculateFileAlignment() {#a0cf1bd036dc392e17aec8733d9a180e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t calculateFileAlignment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; O)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp">MachOUniversalWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/#ad0ac2adcfd6be41ed526a12ddd2215d2">llvm::object::MachOUniversalBinary::MaxSectionAlignment</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aa0720b97729bd97889599a4dc76faf0dc">llvm::MachO::MH_OBJECT</a>.</p>


<p>Referenced by <a href="#ad4f2517d263c6c7cee04ecdcd17a4d7c">calculateAlignment</a>.</p>

</div>
</div>

### getMachoCPUFromObjectFile() {#a46ef10928db52a0401fc0af59f1a2635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachoCPUTy getMachoCPUFromObjectFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; O)</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp">MachOUniversalWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/slice/#adbb4dbd1eb3f1a9959da3bf6baf327e4">llvm::object::Slice::create</a>.</p>

</div>
</div>

### getMachoCPUFromTriple() {#a447fb438fbe4827b7be5fd0a496fe297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; MachoCPUTy &gt; getMachoCPUFromTriple (<a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> TT)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp">MachOUniversalWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3f499fbedb1116d9243b169e32f12367">llvm::MachO::getCPUSubType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ada5bfd87ed7d3e85e1447626b2692055">llvm::MachO::getCPUType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/slice/#adbb4dbd1eb3f1a9959da3bf6baf327e4">llvm::object::Slice::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/slice/#abc9b876b08cdf5b2ec2c2bb13fbf4f65">llvm::object::Slice::create</a> and <a href="#add388c33f2c700c6e3deb6056e996097">getMachoCPUFromTriple</a>.</p>

</div>
</div>

### getMachoCPUFromTriple() {#add388c33f2c700c6e3deb6056e996097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; MachoCPUTy &gt; getMachoCPUFromTriple (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TT)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp">MachOUniversalWriter.cpp</a>.</p>


<p>Reference <a href="#a447fb438fbe4827b7be5fd0a496fe297">getMachoCPUFromTriple</a>.</p>

</div>
</div>

### writeUniversalArchsToStream() {#a9f26efe564d8f7f1afb5f3033156d58d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FatArchTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error writeUniversalArchsToStream (<a href="/web-llvm/docs/api/structs/llvm/macho/fat-header">MachO::fat_header</a> FatHeader, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/slice">Slice</a> &gt; Slices, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp">MachOUniversalWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac65c36245c627cb9fb40879101d952a8">buildFatArchList</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#ac8d6a56e27f4f7bea6b554a42b6024dba767f8f0e00d5de8b4c861e16cbc227f7">llvm::object::FatHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a2036a4973d159e49dcc471488205656f">llvm::MemoryBufferRef::getBufferSize</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a62b2843b74e5f05930ebf5c63766a668">llvm::MemoryBufferRef::getBufferStart</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a754466f4b36d6a2365e56663e0d9de83">llvm::MachO::swapStruct</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a06288f4d38e1d74fc7a1d10056d88373">llvm::raw_ostream::write_zeros</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/object/#a948d67dcc777891db830488aaa2ff78d">llvm::object::writeUniversalBinaryToStream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### FatArchTraits&lt; MachO::fat\_arch &gt;::StructName {#a26ecfcee41769620d62e904e7f142499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string FatArchTraits&lt; MachO::fat_arch &gt;::StructName = "fat_arch"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp">MachOUniversalWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structinfo/#a1476a88b77425ac032a8c9f9cb0f7832">anonymous{MasmParser.cpp}::StructInfo::StructInfo</a> and <a href="/web-llvm/docs/api/structs/anonymous-masmparser-cpp-/structinfo/#a99f9ddc2d0680dbf6e86fae6dee06e9f">anonymous{MasmParser.cpp}::StructInfo::StructInfo</a>.</p>

</div>
</div>

### FatArchTraits&lt; MachO::fat\_arch\_64 &gt;::StructName {#a6714ecab90ae29c500b77df510c3783f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string FatArchTraits&lt; MachO::fat_arch_64 &gt;::StructName = "fat_arch_64"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp">MachOUniversalWriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
