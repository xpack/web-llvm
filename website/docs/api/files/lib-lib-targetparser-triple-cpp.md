---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/targetparser/triple-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Triple.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/swapbyteorder-h">llvm/Support/SwapByteOrder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/versiontuple-h">llvm/Support/VersionTuple.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparser-h">llvm/TargetParser/ARMTargetParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparsercommon-h">llvm/TargetParser/ARMTargetParserCommon.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/host-h">llvm/TargetParser/Host.h</a>"
#include &lt;cassert&gt;
#include &lt;cstring&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154">Triple::ArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabf4024742648721f7840ae35fe7ffd8">parseBPFArch</a> (StringRef ArchName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154">Triple::ArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a721eb5bffb57cea96d7a9b45cbe302cf">parseARMArch</a> (StringRef ArchName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154">Triple::ArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a9a5aa955e9b62ec11e4d3566d4594">parseArch</a> (StringRef ArchName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eec">Triple::VendorType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af928c309977e80665cdc60d0b9c46d89">parseVendor</a> (StringRef VendorName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cd">Triple::OSType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96f0a5c666b924f50da56dede8092ae7">parseOS</a> (StringRef OSName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324">Triple::EnvironmentType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d2990073fc241c3de22309696bf3314">parseEnvironment</a> (StringRef EnvironmentName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201">Triple::ObjectFormatType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd920d1fcd9dc528687e8ab0df027fdd">parseFormat</a> (StringRef EnvironmentName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4">Triple::SubArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac784253baaaa3c7ac2760f3d9b71f1c1">parseSubArch</a> (StringRef SubArchName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201">Triple::ObjectFormatType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a593094f6c13df699bd2cde1a1f40fec4">getDefaultFormat</a> (const Triple &amp;T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a17730f2d2df672ebcf51b00eb2ab55">parseVersionFromName</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ae632cfb346b34a2a80a7f70e1ee048">getDXILArchNameFromShaderModel</a> (StringRef ShaderModelStr)</td>
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

### getDefaultFormat() {#a593094f6c13df699bd2cde1a1f40fec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ObjectFormatType getDefaultFormat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
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



<p>Definition at line 917 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">llvm::Triple::aarch64_32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">llvm::Triple::aarch64_be</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">llvm::Triple::amdgcn</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5ea1b051c09d0127f2d90e0ad6b487df">llvm::Triple::amdil</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ade794c636782fc46854cb047c40c164b">llvm::Triple::amdil64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aed5f38c6bd089f09c02aae8072ceb514">llvm::Triple::arc</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">llvm::Triple::arm</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af65ab1964be676bea302940a45765021">llvm::Triple::armeb</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9b780628857be980e628bf44ae7dce56">llvm::Triple::avr</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154abccdd747b05d7cfff6ae937ffdf5ba03">llvm::Triple::bpfeb</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a83d003d0efa0cd997646dc0343d7093f">llvm::Triple::bpfel</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201aa943abc041caa1cc4c074bbf38b76267">llvm::Triple::COFF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a21a4eb647191d4bd084ffdd749dd9100">llvm::Triple::csky</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a382f97aab858a35311f657a88f998a68">llvm::Triple::DXContainer</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9ca957896440ddfeeedda9c05723c150">llvm::Triple::dxil</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a456b64e26b8bcdbd8294689615d8a055">llvm::Triple::ELF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a7d71851eea2209e547ae06c9c03768f5">llvm::Triple::GOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5770b66a2436004885ac116a8ac357d5">llvm::Triple::hexagon</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aca408a723390395eeaa343d8f1e307c4">llvm::Triple::hsail</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a74533b62667da81390b35d2a47709458">llvm::Triple::hsail64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5c48161b8fa1243dfab0169510c72bb1">llvm::Triple::kalimba</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8ccdc49befcb57d683a4ed2025a7f60d">llvm::Triple::lanai</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0c64155961d19dceb44b43f5a9992d1a">llvm::Triple::loongarch32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">llvm::Triple::loongarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae3dbf1f961e0618ea793bc9c099b932a">llvm::Triple::m68k</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a2ed78f59e2d35011e1d1ed0ad96cf411">llvm::Triple::MachO</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">llvm::Triple::mips</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">llvm::Triple::mips64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">llvm::Triple::mips64el</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">llvm::Triple::mipsel</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a752f0f4d07cf7dcdbe539a95dfe4cbff">llvm::Triple::msp430</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae06ff88d5da98b63a6b4397fcb7a6050">llvm::Triple::nvptx</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a92ac53f0fca7e6c3f4e56a2d4903b9ae">llvm::Triple::nvptx64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">llvm::Triple::ppc</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">llvm::Triple::ppc64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">llvm::Triple::ppc64le</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">llvm::Triple::ppcle</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a060ea888d89f5d59a5743118e429296f">llvm::Triple::r600</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a863d4793e08f6a5a3ca20149b3e7a85d">llvm::Triple::renderscript32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a1c43e5f860c9e21dab6fcfc65f93945d">llvm::Triple::renderscript64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae84559483d0c0f2bddc802ce6f76dd8b">llvm::Triple::riscv32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08">llvm::Triple::riscv64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a396b3f1df93fc8cb904b66759a0d1a96">llvm::Triple::shave</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9ebafd1adc05a751215ae959f2891752">llvm::Triple::sparc</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a069fe14c1b6db6a31124817f2e57c954">llvm::Triple::sparcel</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a34e8fe940082d534b3957f06616c8227">llvm::Triple::sparcv9</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a475e7f13c36b181edba29cfcca212def">llvm::Triple::spir</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5973589725994222a16112b960c74323">llvm::Triple::spir64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201ae057411e10951f5a7dc545e6199c5490">llvm::Triple::SPIRV</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aeee38b63a639e89548c0efc74cab3b65">llvm::Triple::spirv</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154afc429c7efea3699ead2afe26b7db09df">llvm::Triple::spirv32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae0a08d9852914cec82b405e32e87fbdc">llvm::Triple::spirv64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">llvm::Triple::systemz</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ad7837c42372169017a6e5ff3eaa42d1d">llvm::Triple::tce</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8f07c386f3b82ef15a54318946248f96">llvm::Triple::tcele</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">llvm::Triple::thumb</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a038a23cbd1756bf797c083c48229dcfd">llvm::Triple::thumbeb</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda7af47f8e02ca8bd701e40ba03b2bcd95">llvm::Triple::UEFI</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">llvm::Triple::UnknownArch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a419abb6aa1b60e8d534b06311c1e553c">llvm::Triple::ve</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a660d4029da29691e97daf8c8aabb1ffb">llvm::Triple::Wasm</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ac0478f40eaacc5f340e93827756e7a33">llvm::Triple::wasm32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ad6b7ed7027706d2960e771c6374025b1">llvm::Triple::wasm64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdafd0c0a465dca43ad44f79806a226a1ae">llvm::Triple::Win32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a1f7d761ca747e66d2ac0caa0d54b1824">llvm::Triple::XCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a1e3f00d3a8c8c59f0f95fd80f1d3ba53">llvm::Triple::xcore</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab9cc677b26266a0658a4f6feb4ee0bdc">llvm::Triple::xtensa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/triple/#a472091dc314efebea60a6c5cff416cc9">llvm::Triple::setEnvironment</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3a8e516b5874b78eb8bc72e644d62ae5">llvm::Triple::Triple</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a2f144736db0877eaef0c6904afee0187">llvm::Triple::Triple</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a5795a74557bb339afa955660ecb76247">llvm::Triple::Triple</a>.</p>

</div>
</div>

### getDXILArchNameFromShaderModel() {#a9ae632cfb346b34a2a80a7f70e1ee048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getDXILArchNameFromShaderModel (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ShaderModelStr)</td>
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



<p>Definition at line 1086 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9ca957896440ddfeeedda9c05723c150">llvm::Triple::dxil</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a954e732fd72626ce869a6b38c050495d">llvm::Triple::DXILSubArch_v1_0</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a202ec88c46325bdf865ca5a1f5819cb0">llvm::Triple::DXILSubArch_v1_1</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a0e4443406aadf87efa04d1ebeb8bec3a">llvm::Triple::DXILSubArch_v1_2</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a52965fe3bf486e8497500b37cab6273a">llvm::Triple::DXILSubArch_v1_3</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4af083ca354398e0eba40123becd94226f">llvm::Triple::DXILSubArch_v1_4</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a9b088b1eec5001ea047b8bcf2d1e0921">llvm::Triple::DXILSubArch_v1_5</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4ad09a2cbaf1d4a9851a4b332da0616e85">llvm::Triple::DXILSubArch_v1_6</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a959c52d31d7bbee0a429ea61faf01bed">llvm::Triple::DXILSubArch_v1_7</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4ad54b83d8c0ad287435344c7693fbe686">llvm::Triple::DXILSubArch_v1_8</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#ad07e5841d788dc29bdda972b3f92be6b">llvm::VersionTuple::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#ad2d9e5a5c22d594a05d4feae337de252">llvm::Triple::getArchName</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#a56a72b8793b8e0df7217c9b19a83320b">llvm::VersionTuple::getMajor</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#af16679f141c8a480a1e6dcc0b8bcf5de">llvm::VersionTuple::getMinor</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a243270a1b69b4a6ac763fe4317e0528d">llvm::Triple::LatestDXILSubArch</a>, <a href="#a2a17730f2d2df672ebcf51b00eb2ab55">parseVersionFromName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/triple/#a6ac5d7614594ccea16725535d111652a">llvm::Triple::getDXILVersion</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a5c2fb6bace55f9b58ed0ba9fe363299e">llvm::Triple::normalize</a>.</p>

</div>
</div>

### parseArch() {#ad3a9a5aa955e9b62ec11e4d3566d4594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ArchType parseArch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArchName)</td>
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



<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">llvm::Triple::aarch64_32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">llvm::Triple::aarch64_be</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">llvm::Triple::amdgcn</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5ea1b051c09d0127f2d90e0ad6b487df">llvm::Triple::amdil</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ade794c636782fc46854cb047c40c164b">llvm::Triple::amdil64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aed5f38c6bd089f09c02aae8072ceb514">llvm::Triple::arc</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">llvm::Triple::arm</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af65ab1964be676bea302940a45765021">llvm::Triple::armeb</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9b780628857be980e628bf44ae7dce56">llvm::Triple::avr</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a21a4eb647191d4bd084ffdd749dd9100">llvm::Triple::csky</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9ca957896440ddfeeedda9c05723c150">llvm::Triple::dxil</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5770b66a2436004885ac116a8ac357d5">llvm::Triple::hexagon</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aca408a723390395eeaa343d8f1e307c4">llvm::Triple::hsail</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a74533b62667da81390b35d2a47709458">llvm::Triple::hsail64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5c48161b8fa1243dfab0169510c72bb1">llvm::Triple::kalimba</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8ccdc49befcb57d683a4ed2025a7f60d">llvm::Triple::lanai</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0c64155961d19dceb44b43f5a9992d1a">llvm::Triple::loongarch32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">llvm::Triple::loongarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae3dbf1f961e0618ea793bc9c099b932a">llvm::Triple::m68k</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">llvm::Triple::mips</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">llvm::Triple::mips64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">llvm::Triple::mips64el</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">llvm::Triple::mipsel</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a752f0f4d07cf7dcdbe539a95dfe4cbff">llvm::Triple::msp430</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae06ff88d5da98b63a6b4397fcb7a6050">llvm::Triple::nvptx</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a92ac53f0fca7e6c3f4e56a2d4903b9ae">llvm::Triple::nvptx64</a>, <a href="#a721eb5bffb57cea96d7a9b45cbe302cf">parseARMArch</a>, <a href="#aabf4024742648721f7840ae35fe7ffd8">parseBPFArch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">llvm::Triple::ppc</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">llvm::Triple::ppc64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">llvm::Triple::ppc64le</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">llvm::Triple::ppcle</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a060ea888d89f5d59a5743118e429296f">llvm::Triple::r600</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a863d4793e08f6a5a3ca20149b3e7a85d">llvm::Triple::renderscript32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a1c43e5f860c9e21dab6fcfc65f93945d">llvm::Triple::renderscript64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae84559483d0c0f2bddc802ce6f76dd8b">llvm::Triple::riscv32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08">llvm::Triple::riscv64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a396b3f1df93fc8cb904b66759a0d1a96">llvm::Triple::shave</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9ebafd1adc05a751215ae959f2891752">llvm::Triple::sparc</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a069fe14c1b6db6a31124817f2e57c954">llvm::Triple::sparcel</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a34e8fe940082d534b3957f06616c8227">llvm::Triple::sparcv9</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a475e7f13c36b181edba29cfcca212def">llvm::Triple::spir</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5973589725994222a16112b960c74323">llvm::Triple::spir64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aeee38b63a639e89548c0efc74cab3b65">llvm::Triple::spirv</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154afc429c7efea3699ead2afe26b7db09df">llvm::Triple::spirv32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae0a08d9852914cec82b405e32e87fbdc">llvm::Triple::spirv64</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a88e653a89d15149cc7a68f88be360303">llvm::StringSwitch&lt; T, R &gt;::StartsWith</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">llvm::Triple::systemz</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ad7837c42372169017a6e5ff3eaa42d1d">llvm::Triple::tce</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8f07c386f3b82ef15a54318946248f96">llvm::Triple::tcele</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">llvm::Triple::thumb</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a038a23cbd1756bf797c083c48229dcfd">llvm::Triple::thumbeb</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">llvm::Triple::UnknownArch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a419abb6aa1b60e8d534b06311c1e553c">llvm::Triple::ve</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ac0478f40eaacc5f340e93827756e7a33">llvm::Triple::wasm32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ad6b7ed7027706d2960e771c6374025b1">llvm::Triple::wasm64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a1e3f00d3a8c8c59f0f95fd80f1d3ba53">llvm::Triple::xcore</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab9cc677b26266a0658a4f6feb4ee0bdc">llvm::Triple::xtensa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a8baeb4d23f981eda5c951371da480b99">llvm::ARM::getDefaultCPU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#a8e20a1515e9e84624e4dc843d115f172">llvm::CSKY::getDefaultCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5c2fb6bace55f9b58ed0ba9fe363299e">llvm::Triple::normalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a96deed10d8fd592dce3db1b8d8df6011">llvm::ARM::parseArchProfile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#aad4536fc71bd7d65d3c704ca2f9073f1">llvm::ARM::parseArchVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3a8e516b5874b78eb8bc72e644d62ae5">llvm::Triple::Triple</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a2f144736db0877eaef0c6904afee0187">llvm::Triple::Triple</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a5795a74557bb339afa955660ecb76247">llvm::Triple::Triple</a>.</p>

</div>
</div>

### parseARMArch() {#a721eb5bffb57cea96d7a9b45cbe302cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ArchType parseARMArch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArchName)</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/arm/#aa7c564eb9f55772c4e2f4d3c19974191a036a8f756db6f6db7e1ed8f22a9f641e">llvm::ARM::AARCH64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">llvm::Triple::aarch64_be</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#aa7c564eb9f55772c4e2f4d3c19974191a47f45e65244c17ec9fa8771a5c6d60e1">llvm::ARM::ARM</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">llvm::Triple::arm</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af65ab1964be676bea302940a45765021">llvm::Triple::armeb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a744a4278ab4117a12d8d7bd90fa009d0aa60c6c694491d75b439073b8cb05b139">llvm::ARM::BIG</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a115dd532d6538ed40f42a625343126cc">llvm::ARM::getCanonicalArchName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#aa7c564eb9f55772c4e2f4d3c19974191accc0377a8afbf50e7094f5c23a8af223">llvm::ARM::INVALID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a744a4278ab4117a12d8d7bd90fa009d0a1314341b466dcb5e2c880b76414c49fe">llvm::ARM::LITTLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ac2456158e5acb44477d8ecfa2d04dbdea69691c7bdcc3ce6d5d8a1361f22d04ac">llvm::ARM::M</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ac9eb980260cef7839596d3ca4d742905">llvm::ARM::parseArchEndian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a1d5ed0bfc1c21767207fbd9c06aa68e9">llvm::ARM::parseArchISA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a96deed10d8fd592dce3db1b8d8df6011">llvm::ARM::parseArchProfile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#aad4536fc71bd7d65d3c704ca2f9073f1">llvm::ARM::parseArchVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp/#a009775794ead70aa23c76df46ab4ed8a">Profile</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#aa7c564eb9f55772c4e2f4d3c19974191ae466500055d2302ad1956d15e96a129a">llvm::ARM::THUMB</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">llvm::Triple::thumb</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a038a23cbd1756bf797c083c48229dcfd">llvm::Triple::thumbeb</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">llvm::Triple::UnknownArch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="#ad3a9a5aa955e9b62ec11e4d3566d4594">parseArch</a>.</p>

</div>
</div>

### parseBPFArch() {#aabf4024742648721f7840ae35fe7ffd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ArchType parseBPFArch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArchName)</td>
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



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154abccdd747b05d7cfff6ae937ffdf5ba03">llvm::Triple::bpfeb</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a83d003d0efa0cd997646dc0343d7093f">llvm::Triple::bpfel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">llvm::Triple::UnknownArch</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/triple/#a5d5efe3bb966ce825560b2e6dd46f8ec">llvm::Triple::getArchTypeForLLVMName</a> and <a href="#ad3a9a5aa955e9b62ec11e4d3566d4594">parseArch</a>.</p>

</div>
</div>

### parseEnvironment() {#a1d2990073fc241c3de22309696bf3314}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::EnvironmentType parseEnvironment (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EnvironmentName)</td>
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



<p>Definition at line 717 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ab926bec66aeb0288525973f203bcb94a">llvm::Triple::Amplification</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a0ceb06180ab5fc86e9ad27563b538439">llvm::Triple::Android</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ab73388cc76387a636177ac9e405d0b39">llvm::Triple::AnyHit</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324adf4a58c1d4eb1aeba280a3fc580e9f8d">llvm::Triple::Callable</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a783d818fcc0a9d1e095674aa7b255082">llvm::Triple::ClosestHit</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ace5d58a24effb264483f4af8b79b97b2">llvm::Triple::CODE16</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a35a7d7865588f76c4f300fb1f07ee1bc">llvm::Triple::Compute</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324afcb832e2cb16856e53500d3c1e52a890">llvm::Triple::CoreCLR</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a0521408131ca98c3ee4f486df216ea39">llvm::Triple::Cygnus</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a9250a1f506b7407b838bf0b494f9cd33">llvm::Triple::Domain</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a847a953f3f994ab5453f075cea9ca7af">llvm::Triple::EABI</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324af2b02c10c51141fdaa4cb49402e20169">llvm::Triple::EABIHF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ade3aad57a34a47654ebeee1a2d4ab960">llvm::Triple::Geometry</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ae6c91532448c0be7978cf1bfcdaa11bb">llvm::Triple::GNU</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a21e1198b41cc86aafe10fcd5a6ca330b">llvm::Triple::GNUABI64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a75fa362b8315ce952fde83ff09a4c599">llvm::Triple::GNUABIN32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a73b4a675dd734e1efcab33de0d217a37">llvm::Triple::GNUEABI</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a699fcd7db202863a2a82143681dadb85">llvm::Triple::GNUEABIHF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ae5c77cfc976654fac7f3f50ee1352a8e">llvm::Triple::GNUEABIHFT64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a2343e70ca8369c9a61e3e25aa4e08216">llvm::Triple::GNUEABIT64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a61ce851e1f60ad25421987629f5ac2c2">llvm::Triple::GNUF32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a587bfd81081ee91855e23c7cc05d4487">llvm::Triple::GNUF64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a0a05a130bb4b1c97244ff98d64e0de5d">llvm::Triple::GNUILP32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a9953bc1a6bb23d4a733faf9afb0df99a">llvm::Triple::GNUSF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a648404ce7e68eb5d5a6c60afa8744438">llvm::Triple::GNUT64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ab0c4c38b98e3b1482fc1c5afc8649e28">llvm::Triple::GNUX32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ac8bc9b9934c75b722dcdde3b705c0a51">llvm::Triple::Hull</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ac5ff0a8f8e278b84cdd8518a6e0c67d8">llvm::Triple::Intersection</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324aa97aa42b85b1502e458177c354ab6788">llvm::Triple::Itanium</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a38ed328b8551b06c5a133e54867110bf">llvm::Triple::Library</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a40176fd51bd652566e1d48b5455fd081">llvm::Triple::LLVM</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a0a522a127e133d8cd07fa678e6672695">llvm::Triple::MacABI</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324aa1a97c079fbb80fcd9ab0f5fa24f3025">llvm::Triple::Mesh</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ad6c99823a0c7477c6412728485bb0fe7">llvm::Triple::Miss</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a6d53dbdf9a8b9b1092558cf23f83a95a">llvm::Triple::MSVC</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a332336ad935952ff734309ce432de6d1">llvm::Triple::Musl</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a27355a1eadfe9594a7acc5634d54bfc8">llvm::Triple::MuslABI64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a07818ec9990bfc4675291f2235ab6e8b">llvm::Triple::MuslABIN32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a8a7dd3fc84b97dc5b1a677d60e46df80">llvm::Triple::MuslEABI</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ab711c5b8f1cd078c75864af125d07fef">llvm::Triple::MuslEABIHF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a66008454cd4031dad58b64c0eae7f9e4">llvm::Triple::MuslF32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324aff5daa73e757da85e8803ea0e323d5b0">llvm::Triple::MuslSF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ae2e0845b94acce4ef8966096195201dd">llvm::Triple::MuslX32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a8a0496f998fd9139553edc0ef61c2cc4">llvm::Triple::OpenCL</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a582eb6a495698055109b21d02b959c2e">llvm::Triple::OpenHOS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a74151519e4fd7f222963d600ad2d44b5">llvm::Triple::PAuthTest</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a4bd403d91c4535171833f92e0ce36137">llvm::Triple::Pixel</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a15bc4c083c1cda54e3011297b4bf8351">llvm::Triple::RayGeneration</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a587146bd8be66f0980d55ca2664c5642">llvm::Triple::Simulator</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a88e653a89d15149cc7a68f88be360303">llvm::StringSwitch&lt; T, R &gt;::StartsWith</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a6c32bcd90dff79307baf3147697ae1d3">llvm::Triple::UnknownEnvironment</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a71b983b2a1bf8a46c5ac7d21de26fb4a">llvm::Triple::Vertex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/triple/#a5c2fb6bace55f9b58ed0ba9fe363299e">llvm::Triple::normalize</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a2f144736db0877eaef0c6904afee0187">llvm::Triple::Triple</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a5795a74557bb339afa955660ecb76247">llvm::Triple::Triple</a>.</p>

</div>
</div>

### parseFormat() {#acd920d1fcd9dc528687e8ab0df027fdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ObjectFormatType parseFormat (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EnvironmentName)</td>
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



<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201aa943abc041caa1cc4c074bbf38b76267">llvm::Triple::COFF</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a456b64e26b8bcdbd8294689615d8a055">llvm::Triple::ELF</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#aa50a7b1fb270f50ee5fe0db126b9f75f">llvm::StringSwitch&lt; T, R &gt;::EndsWith</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a7d71851eea2209e547ae06c9c03768f5">llvm::Triple::GOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a2ed78f59e2d35011e1d1ed0ad96cf411">llvm::Triple::MachO</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201ae057411e10951f5a7dc545e6199c5490">llvm::Triple::SPIRV</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201af2f88d8b470958614a01866d4714b5a4">llvm::Triple::UnknownObjectFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a660d4029da29691e97daf8c8aabb1ffb">llvm::Triple::Wasm</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a1f7d761ca747e66d2ac0caa0d54b1824">llvm::Triple::XCOFF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/triple/#a5c2fb6bace55f9b58ed0ba9fe363299e">llvm::Triple::normalize</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a2f144736db0877eaef0c6904afee0187">llvm::Triple::Triple</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a5795a74557bb339afa955660ecb76247">llvm::Triple::Triple</a>.</p>

</div>
</div>

### parseOS() {#a96f0a5c666b924f50da56dede8092ae7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::OSType parseOS (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> OSName)</td>
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



<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda55c9e8cff2a0eab89d1b234d419ee93f">llvm::Triple::AIX</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda0a0dddcf03f8f66f7c13558b3c81d845">llvm::Triple::AMDHSA</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda7d8eb2c700c876375f588d68dc692f15">llvm::Triple::AMDPAL</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdac1302c2bd5aa5a28b3558b748e57e6ea">llvm::Triple::BridgeOS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdac81124e2bdd6fb0d7b3fc4bd30233928">llvm::Triple::CUDA</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda0824a8c56de913d60c6f55edc0ac3148">llvm::Triple::Darwin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda0e7175bb9a8eea9efd2a5e50b6ca84ab">llvm::Triple::DragonFly</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda600aa0b72f321a0cdf0e4b3f38b9b6c8">llvm::Triple::DriverKit</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdaea39dbcca2c32c044d958aceb371bb13">llvm::Triple::ELFIAMCU</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdae7c70b9eb6106c04f131eca1e3be44ac">llvm::Triple::Emscripten</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda64fc6929b84f845ced55d3313ebcf423">llvm::Triple::FreeBSD</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdaad44ff9454db9e8eb2e38d964f0345b7">llvm::Triple::Fuchsia</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda55732429424dd801e57c7c667a8d4217">llvm::Triple::Haiku</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda5523c4eadf302b516ae738ddf52076a5">llvm::Triple::HermitCore</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdaf17d175b40b8e7ceedc92aea3929eb27">llvm::Triple::Hurd</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdafad6e6763679be1478d9283a7344d243">llvm::Triple::IOS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda6506444610ddf1a927cf919508b2ea1b">llvm::Triple::KFreeBSD</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda76d4dd8dc67e3a11d975743f6d63a9df">llvm::Triple::Linux</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdaf7d25a9254177b6890fd8c115503014d">llvm::Triple::LiteOS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda379ed41d00eaa4c446cdefc892d8762f">llvm::Triple::Lv2</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075">llvm::Triple::MacOSX</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda81cc47a265b37fea8b5b3575b67ea6ed">llvm::Triple::Mesa3D</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdaae17c480f3a0e37421e04400dca90d1b">llvm::Triple::NaCl</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdad10d236fcf52bdbf36bd6b401ca9e427">llvm::Triple::NetBSD</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda6f69427cfc546c2402cdbee116ca6af9">llvm::Triple::NVCL</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda13c01bda5d01cb2264a0cebe7b411c54">llvm::Triple::OpenBSD</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda63d6dc93c7b6ab41ba169620a639bec1">llvm::Triple::PS4</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda683700aa7afbff16fe3885d5ad05923c">llvm::Triple::PS5</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda638da1f392b8b391c2af80e9d461d17b">llvm::Triple::RTEMS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda3abcbc3caa438ea915121cdf3d373aae">llvm::Triple::Serenity</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdac4081e09efdc53c28fc78e5ca68ea70a">llvm::Triple::ShaderModel</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdac44628c2fbd9505dc608a330838fccce">llvm::Triple::Solaris</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a88e653a89d15149cc7a68f88be360303">llvm::StringSwitch&lt; T, R &gt;::StartsWith</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda2838cf6df0f09591c50d752d46c4350d">llvm::Triple::TvOS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda7af47f8e02ca8bd701e40ba03b2bcd95">llvm::Triple::UEFI</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda4b110a50637320a1a0db33999b809ddd">llvm::Triple::UnknownOS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda844b53b7eb8188bdea24d4147b10d2b3">llvm::Triple::Vulkan</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdab4b12e4f268dff8ead7f9194ee8da04b">llvm::Triple::WASI</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda87a3c8454473c64f6d605ebd757759ad">llvm::Triple::WatchOS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdafd0c0a465dca43ad44f79806a226a1ae">llvm::Triple::Win32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdabb5225659a201976ce2594df579e3623">llvm::Triple::XROS</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdafd36ac5f07b0474e2b5c167ab7158538">llvm::Triple::ZOS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/triple/#a5c2fb6bace55f9b58ed0ba9fe363299e">llvm::Triple::normalize</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3a8e516b5874b78eb8bc72e644d62ae5">llvm::Triple::Triple</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a2f144736db0877eaef0c6904afee0187">llvm::Triple::Triple</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a5795a74557bb339afa955660ecb76247">llvm::Triple::Triple</a>.</p>

</div>
</div>

### parseSubArch() {#ac784253baaaa3c7ac2760f3d9b71f1c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::SubArchType parseSubArch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SubArchName)</td>
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



<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a68fc64acd599f1efceab58c5b1c948c1">llvm::Triple::AArch64SubArch_arm64e</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4ac4c8930e0836b52270b435d71f98bdb0">llvm::Triple::AArch64SubArch_arm64ec</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4accd10f70cf09c8a1612e20f13675f06c">llvm::Triple::ARMSubArch_v4t</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a65a1a4e325bfede2c90fe1a5c6133bb2">llvm::Triple::ARMSubArch_v5</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4ac7b6c0c4bacdf3e9f70a4d97348fce9e">llvm::Triple::ARMSubArch_v5te</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a6f712f6f866568eb3e0b2f7aa652fa35">llvm::Triple::ARMSubArch_v6</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a5e3ffc6475a86a4e2040e08b27dab792">llvm::Triple::ARMSubArch_v6k</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4adcfb053d1ad63024466047a1c6a92ff3">llvm::Triple::ARMSubArch_v6m</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a01fcbdd4fbb3ddfc02aeeea9de057404">llvm::Triple::ARMSubArch_v6t2</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a0ebf9bc3153a34e39fb7f2b5adc4a549">llvm::Triple::ARMSubArch_v7</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4ab8efff655ba87c9dfdd350b51a3d4345">llvm::Triple::ARMSubArch_v7em</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a310c3af47d446eeaea76dd7ce69241f5">llvm::Triple::ARMSubArch_v7k</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a56d9342dc07ff0e1a21a3906fe31957c">llvm::Triple::ARMSubArch_v7m</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a8c30db3aef5173efcffcfbb21a083a64">llvm::Triple::ARMSubArch_v7s</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a7688e046378ef49d94118935e9bdc139">llvm::Triple::ARMSubArch_v7ve</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a476c85c6da91c99d7aaade451bd18361">llvm::Triple::ARMSubArch_v8</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a4e8c5a248d17f31e627d9105ddeef945">llvm::Triple::ARMSubArch_v8_1a</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4ac0e610ea380b0a0ebb52353ed1a0b1cd">llvm::Triple::ARMSubArch_v8_1m_mainline</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a8ae0544e8c0ae188e328279be14e4e53">llvm::Triple::ARMSubArch_v8_2a</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4ac455352f512fd2d68d7ee647d53f350d">llvm::Triple::ARMSubArch_v8_3a</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4aa61c5037a2303b17579ddecb3b9e224e">llvm::Triple::ARMSubArch_v8_4a</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4ad98b7c5865d2b36266806520861920ea">llvm::Triple::ARMSubArch_v8_5a</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4ac6acea60433ffb675553d7e1b5be256e">llvm::Triple::ARMSubArch_v8_6a</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a40920b0d5d8769714a371fcf155602f8">llvm::Triple::ARMSubArch_v8_7a</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a78ec4bc30363cbd6e87200a8b55340e8">llvm::Triple::ARMSubArch_v8_8a</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4aaf8f8301b1acd585a755ca14ab6e333b">llvm::Triple::ARMSubArch_v8_9a</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a782e22ec2166acb2925666b1fdcf87be">llvm::Triple::ARMSubArch_v8m_baseline</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a0f762073e648e99a9513ac450cae6504">llvm::Triple::ARMSubArch_v8m_mainline</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a1185d2fec5230b7b356db168f5b33b8d">llvm::Triple::ARMSubArch_v8r</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4ae60c9fe88a53cb6def09bc5b5137fe8d">llvm::Triple::ARMSubArch_v9</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a185d6eb97a379483b3c3a4284cd45cc2">llvm::Triple::ARMSubArch_v9_1a</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a50198e2c009206d54f69a1ed6f457fe3">llvm::Triple::ARMSubArch_v9_2a</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4adde68b7158745bbd00b1320768e2ca23">llvm::Triple::ARMSubArch_v9_3a</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4ad5841034e27eba09d31d90905cc0974b">llvm::Triple::ARMSubArch_v9_4a</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a730333b03ef48149676803658abe7196">llvm::Triple::ARMSubArch_v9_5a</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a110b3a4de8e1b2d76335c6eb299a22f9">llvm::Triple::ARMSubArch_v9_6a</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a954e732fd72626ce869a6b38c050495d">llvm::Triple::DXILSubArch_v1_0</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a202ec88c46325bdf865ca5a1f5819cb0">llvm::Triple::DXILSubArch_v1_1</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a0e4443406aadf87efa04d1ebeb8bec3a">llvm::Triple::DXILSubArch_v1_2</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a52965fe3bf486e8497500b37cab6273a">llvm::Triple::DXILSubArch_v1_3</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4af083ca354398e0eba40123becd94226f">llvm::Triple::DXILSubArch_v1_4</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a9b088b1eec5001ea047b8bcf2d1e0921">llvm::Triple::DXILSubArch_v1_5</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4ad09a2cbaf1d4a9851a4b332da0616e85">llvm::Triple::DXILSubArch_v1_6</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a959c52d31d7bbee0a429ea61faf01bed">llvm::Triple::DXILSubArch_v1_7</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4ad54b83d8c0ad287435344c7693fbe686">llvm::Triple::DXILSubArch_v1_8</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aca439bf65258d9d8d057812938b617c5">llvm::StringRef::ends_with</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#aa50a7b1fb270f50ee5fe0db126b9f75f">llvm::StringSwitch&lt; T, R &gt;::EndsWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a115dd532d6538ed40f42a625343126cc">llvm::ARM::getCanonicalArchName</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a977ada971b681fd292c46b933b179a2d">llvm::Triple::KalimbaSubArch_v3</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4abf52302217787a19c1c051caf6e9846a">llvm::Triple::KalimbaSubArch_v4</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4acb11740734f6a18e96b94096142157e3">llvm::Triple::KalimbaSubArch_v5</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a06ae0d5f23c7c3ab80c4a241a7489385">llvm::Triple::MipsSubArch_r6</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a023f1e73b058ea58dba15516382eed52">llvm::Triple::NoSubArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a75e18d4bc8fef7e89c1222c6b6cf8638">llvm::ARM::parseArch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4af9352d351703c7abc15682e3cacbd872">llvm::Triple::PPCSubArch_spe</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a28f0d364a91de157afe87b7a37f4482f">llvm::Triple::SPIRVSubArch_v10</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4af683dac34822e36580d0a321f68af416">llvm::Triple::SPIRVSubArch_v11</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4abbfc31485ff4538616ec4781b43e84ed">llvm::Triple::SPIRVSubArch_v12</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a2aa494dc61832706e97f2e3754d08fed">llvm::Triple::SPIRVSubArch_v13</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4abe4d0a4aeeee8ba9fad55d5be3375c0a">llvm::Triple::SPIRVSubArch_v14</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a56d1bb97744ae0c6b4a62d7057b8b3c9">llvm::Triple::SPIRVSubArch_v15</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4a4c3a9a3e3252bd79135d70a26bffb83b">llvm::Triple::SPIRVSubArch_v16</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/triple/#a3a8e516b5874b78eb8bc72e644d62ae5">llvm::Triple::Triple</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a2f144736db0877eaef0c6904afee0187">llvm::Triple::Triple</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a5795a74557bb339afa955660ecb76247">llvm::Triple::Triple</a>.</p>

</div>
</div>

### parseVendor() {#af928c309977e80665cdc60d0b9c46d89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::VendorType parseVendor (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> VendorName)</td>
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



<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eeca77be73c19a4451fa0580ac5b9018357b">llvm::Triple::AMD</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eeca674d908c8b0ebe1880f8c8d651eda9e2">llvm::Triple::Apple</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eecaf2892bfd7e664cbdc7ced8ae9c15ca33">llvm::Triple::CSR</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eeca919656f12c161f60c585b6ea65c77f9a">llvm::Triple::Freescale</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eecae7589347388e13a416edcb71a946416c">llvm::Triple::IBM</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eeca9e259de1548e02615004c538112d3aab">llvm::Triple::ImaginationTechnologies</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eecac949231cdefe4cbb0f48febd5fda4ce7">llvm::Triple::Intel</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eecaa29f6dfe49ede82d55ad9310efd3582c">llvm::Triple::Mesa</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eecadc6b40589adfbd4756bf72561c69a8c3">llvm::Triple::MipsTechnologies</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eecaeb014b23b113a1cda5058e4e31aca881">llvm::Triple::NVIDIA</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eeca5881a9306181e4330e92688656a52f4c">llvm::Triple::OpenEmbedded</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eecafbca4de1e7e0ce699db11feb6a205b32">llvm::Triple::PC</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eecaf8cf55a2ccb688a02134bd768c9a1a3d">llvm::Triple::SCEI</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eeca841dde16a0ee702c5b7aeda162c85e0c">llvm::Triple::SUSE</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eeca0f632276cf5b78ab97257d7f90b7f97f">llvm::Triple::UnknownVendor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/triple/#a5c2fb6bace55f9b58ed0ba9fe363299e">llvm::Triple::normalize</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3a8e516b5874b78eb8bc72e644d62ae5">llvm::Triple::Triple</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a2f144736db0877eaef0c6904afee0187">llvm::Triple::Triple</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a5795a74557bb339afa955660ecb76247">llvm::Triple::Triple</a>.</p>

</div>
</div>

### parseVersionFromName() {#a2a17730f2d2df672ebcf51b00eb2ab55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple parseVersionFromName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 1380 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp">Triple.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="#a9ae632cfb346b34a2a80a7f70e1ee048">getDXILArchNameFromShaderModel</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a6ac5d7614594ccea16725535d111652a">llvm::Triple::getDXILVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5ad45f83c98f9639777cb9924cef58fd">llvm::Triple::getEnvironmentVersion</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a024faa768c9d7b624a68980113f92693">llvm::Triple::getOSVersion</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
