---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/memprof/portablememinfoblock
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PortableMemInfoBlock` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::memprof::PortableMemInfoBlock { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">llvm/ProfileData/MemProf.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd06c0ab94821fa935e3d4a822488e6c">yaml::CustomMappingTraits&lt; memprof::PortableMemInfoBlock &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b4243ef7b3a6e17d1d2616eea8df84">PortableMemInfoBlock</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae61991eb1f81d6073d6e50832a28ddd6">PortableMemInfoBlock</a> (const MemInfoBlock &amp;Block, const MemProfSchema &amp;IncomingSchema)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a293a73a87b49b4542c2f82c1b01494a8">PortableMemInfoBlock</a> (const MemProfSchema &amp;Schema, const unsigned char *Ptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebf3d98082128980f52ce8192524570b">operator==</a> (const PortableMemInfoBlock &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bb46cdb00161890b5f1a63cb9278843">operator!=</a> (const PortableMemInfoBlock &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fe59fa6a9869041f3d4a7628b047ac3">deserialize</a> (const MemProfSchema &amp;IncomingSchema, const unsigned char *Ptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc4d6cca2bd9997078d0dcd72cad45a2">serialize</a> (const MemProfSchema &amp;Schema, raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4f5f9d64423198132a7679d93dca9d7">printYAML</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::bitset&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a842e49a58fb3eba4e42a8dadad77745b">llvm::to_underlying</a>(Meta::Size)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79eb2495fa4e516b0a777f71a491fe77">getSchema</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae3dcb322e42bb0e0f270af06c45fcf4">MIBEntryDef</a> (AllocCount=1, AllocCount, uint32_t) MIBEntryDef(TotalAccessCount</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a241d9cbb9abd287496ce9145bf513026">MIBEntryDef</a> (MinAccessCount=3, MinAccessCount, uint64_t) MIBEntryDef(MaxAccessCount</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b7db611cdf455ef0db7398fc17f4e09">MIBEntryDef</a> (TotalSize=5, TotalSize, uint64_t) MIBEntryDef(MinSize</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d50e96ce809f6939fdf37e9acbd8376">MIBEntryDef</a> (MaxSize=7, MaxSize, uint32_t) MIBEntryDef(AllocTimestamp</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af43c12a717081ef222676fae6bf27e4c">MIBEntryDef</a> (DeallocTimestamp=9, DeallocTimestamp, uint32_t) MIBEntryDef(TotalLifetime</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac13307a1e83eb1342cd9b4867b2db842">MIBEntryDef</a> (MinLifetime=11, MinLifetime, uint32_t) MIBEntryDef(MaxLifetime</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac34411958bcccc36073807812f0230ba">MIBEntryDef</a> (AllocCpuId=13, AllocCpuId, uint32_t) MIBEntryDef(DeallocCpuId</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa820a27df40941f74e3f8fbc1e7efca2">MIBEntryDef</a> (NumMigratedCpu=15, NumMigratedCpu, uint32_t) MIBEntryDef(NumLifetimeOverlaps</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a49b5403483facaf1acf76a0d997851">MIBEntryDef</a> (NumSameAllocCpu=17, NumSameAllocCpu, uint32_t) MIBEntryDef(NumSameDeallocCpu</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc9d73fe3258e7e306fbb3d44d24f9f4">MIBEntryDef</a> (DataTypeId=19, DataTypeId, uint64_t) MIBEntryDef(TotalAccessDensity</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5acabbbf5962721e242af51b4d005e7">MIBEntryDef</a> (MinAccessDensity=21, MinAccessDensity, uint32_t) MIBEntryDef(MaxAccessDensity</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cd082c17748e8a6983b81e2dc3f174d">MIBEntryDef</a> (TotalLifetimeAccessDensity=23, TotalLifetimeAccessDensity, uint64_t) MIBEntryDef(MinLifetimeAccessDensity</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63b47eba30f5b44c44fc365ab9ca613">MIBEntryDef</a> (MaxLifetimeAccessDensity=25, MaxLifetimeAccessDensity, uint32_t) MIBEntryDef(AccessHistogramSize</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01165bba4ba67be1ff76aa478de7721a">MIBEntryDef</a> (AccessHistogram=27, AccessHistogram, uintptr_t) MIBEntryDef(AllocCount</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4482fe2436110d9157c42a264135b006">MIBEntryDef</a> (TotalAccessCount=2, TotalAccessCount, uint64_t) MIBEntryDef(MinAccessCount</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bb0fb7a42b5f66f0a4cffbf33ff999e">MIBEntryDef</a> (MaxAccessCount=4, MaxAccessCount, uint64_t) MIBEntryDef(TotalSize</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7ca54aa36c84d9489fefd04fd2afa02">MIBEntryDef</a> (MinSize=6, MinSize, uint32_t) MIBEntryDef(MaxSize</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfb2013d3e46bba1a42f0dfba612795f">MIBEntryDef</a> (AllocTimestamp=8, AllocTimestamp, uint32_t) MIBEntryDef(DeallocTimestamp</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25ed396e4204815792c382667f27d4f0">MIBEntryDef</a> (TotalLifetime=10, TotalLifetime, uint64_t) MIBEntryDef(MinLifetime</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3e52367a1ac1b47fed71334f7db38fd">MIBEntryDef</a> (MaxLifetime=12, MaxLifetime, uint32_t) MIBEntryDef(AllocCpuId</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ca33eb453cce3aebb589cbf249f7439">MIBEntryDef</a> (DeallocCpuId=14, DeallocCpuId, uint32_t) MIBEntryDef(NumMigratedCpu</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19decb6d90f34308cc44a893db0c84c2">MIBEntryDef</a> (NumLifetimeOverlaps=16, NumLifetimeOverlaps, uint32_t) MIBEntryDef(NumSameAllocCpu</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a90c90a746fbb5f3b3e37085bd285ff">MIBEntryDef</a> (NumSameDeallocCpu=18, NumSameDeallocCpu, uint32_t) MIBEntryDef(DataTypeId</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac430de2a945a7102ca202eee0f0ad50a">MIBEntryDef</a> (TotalAccessDensity=20, TotalAccessDensity, uint64_t) MIBEntryDef(MinAccessDensity</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eb23a9aece97c0cc4e0f4066bb8d41f">MIBEntryDef</a> (MaxAccessDensity=22, MaxAccessDensity, uint32_t) MIBEntryDef(TotalLifetimeAccessDensity</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6771ff046d637aaed03100cbae0d069d">MIBEntryDef</a> (MinLifetimeAccessDensity=24, MinLifetimeAccessDensity, uint32_t) MIBEntryDef(MaxLifetimeAccessDensity</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b3cbd3f8cae0d97779e8c1fd78a1207">MIBEntryDef</a> (AccessHistogramSize=26, AccessHistogramSize, uint32_t) MIBEntryDef(AccessHistogram</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint64_t uint32_t uintptr_t void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae956e23e4548a0b2cd52be9d60771217">clear</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae3dcb322e42bb0e0f270af06c45fcf4">MIBEntryDef</a> (AllocCount=1, AllocCount, uint32_t) MIBEntryDef(TotalAccessCount</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a241d9cbb9abd287496ce9145bf513026">MIBEntryDef</a> (MinAccessCount=3, MinAccessCount, uint64_t) MIBEntryDef(MaxAccessCount</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b7db611cdf455ef0db7398fc17f4e09">MIBEntryDef</a> (TotalSize=5, TotalSize, uint64_t) MIBEntryDef(MinSize</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d50e96ce809f6939fdf37e9acbd8376">MIBEntryDef</a> (MaxSize=7, MaxSize, uint32_t) MIBEntryDef(AllocTimestamp</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af43c12a717081ef222676fae6bf27e4c">MIBEntryDef</a> (DeallocTimestamp=9, DeallocTimestamp, uint32_t) MIBEntryDef(TotalLifetime</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac13307a1e83eb1342cd9b4867b2db842">MIBEntryDef</a> (MinLifetime=11, MinLifetime, uint32_t) MIBEntryDef(MaxLifetime</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac34411958bcccc36073807812f0230ba">MIBEntryDef</a> (AllocCpuId=13, AllocCpuId, uint32_t) MIBEntryDef(DeallocCpuId</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa820a27df40941f74e3f8fbc1e7efca2">MIBEntryDef</a> (NumMigratedCpu=15, NumMigratedCpu, uint32_t) MIBEntryDef(NumLifetimeOverlaps</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a49b5403483facaf1acf76a0d997851">MIBEntryDef</a> (NumSameAllocCpu=17, NumSameAllocCpu, uint32_t) MIBEntryDef(NumSameDeallocCpu</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc9d73fe3258e7e306fbb3d44d24f9f4">MIBEntryDef</a> (DataTypeId=19, DataTypeId, uint64_t) MIBEntryDef(TotalAccessDensity</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5acabbbf5962721e242af51b4d005e7">MIBEntryDef</a> (MinAccessDensity=21, MinAccessDensity, uint32_t) MIBEntryDef(MaxAccessDensity</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cd082c17748e8a6983b81e2dc3f174d">MIBEntryDef</a> (TotalLifetimeAccessDensity=23, TotalLifetimeAccessDensity, uint64_t) MIBEntryDef(MinLifetimeAccessDensity</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63b47eba30f5b44c44fc365ab9ca613">MIBEntryDef</a> (MaxLifetimeAccessDensity=25, MaxLifetimeAccessDensity, uint32_t) MIBEntryDef(AccessHistogramSize</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c7301eef4644f34b8715023f3d665e3">TotalAccessCount</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a3d9fafa313c7237f67e90e1c07ece6">MaxAccessCount</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5d7e361735593dd000570a0875f078a">MinSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b1c7bb733eb271e5724e2195b1363da">AllocTimestamp</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ddccf17449bdfaf8531484864842837">TotalLifetime</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef4c74c81344ea711dba09e17b361858">MaxLifetime</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa24623fced1e91c425be64407545a64a">DeallocCpuId</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a793d215aa9b965406a8e0a3d2af19e4c">NumLifetimeOverlaps</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39ce04b4cc9a736794fe3d3a9321dece">NumSameDeallocCpu</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af23cd84e74cd9d010997dfe855bea2c2">TotalAccessDensity</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef84b4330545b5d4b1185dea238cebdb">MaxAccessDensity</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76f2748c6822dbcd8a361cf05fc666ab">MinLifetimeAccessDensity</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5012ee6358ef6abeb3fa7112eff5ab76">AccessHistogramSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16d46a1dad67ea4e7a64523df705682e">AllocCount</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e90d98fea2337722579602a547d180c">MinAccessCount</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a2bc58a7513c1ab8cbf51e3415d6851">TotalSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25c6f708cd8c864a479f891a831ea888">MaxSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae80b67790bdda40296ca4c6f92a87a11">DeallocTimestamp</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2924ec336b30c5c27df1a44f4eb7809">MinLifetime</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af007689fcd73286fb2abcd1d39c4bfcb">AllocCpuId</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba0a772fc9b6a0136a541fde0e536380">NumMigratedCpu</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3156129271b943e3fdd86b0700b58ec">NumSameAllocCpu</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90450d0f9244f22fd2251e3adf6f0622">DataTypeId</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74ffbe21916456f1d3f2cc25b1037479">MinAccessDensity</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27b66ff857980a3b4164001f7b16507e">TotalLifetimeAccessDensity</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa764e9bb29966a2eeb623b182439b966">MaxLifetimeAccessDensity</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee68e58fcdbed6070dca830978aeaf27">AccessHistogram</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::bitset&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a842e49a58fb3eba4e42a8dadad77745b">llvm::to_underlying</a>(Meta::Size)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcd194645d23808a8e179cba21d0e504">Schema</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c040a57b4b47b1a20651b401b367b94">serializedSize</a> (const MemProfSchema &amp;Schema)</td>
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


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<div class="doxySectionDef">

## Friends

### yaml::CustomMappingTraits&lt; memprof::PortableMemInfoBlock &gt; {#afd06c0ab94821fa935e3d4a822488e6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits">yaml::CustomMappingTraits</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/memprof/portablememinfoblock">memprof::PortableMemInfoBlock</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PortableMemInfoBlock() {#a51b4243ef7b3a6e17d1d2616eea8df84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::PortableMemInfoBlock::PortableMemInfoBlock ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>Referenced by <a href="#ae956e23e4548a0b2cd52be9d60771217">clear</a>, <a href="#a0bb46cdb00161890b5f1a63cb9278843">operator!=</a> and <a href="#aebf3d98082128980f52ce8192524570b">operator==</a>.</p>

</div>
</div>

### PortableMemInfoBlock() {#ae61991eb1f81d6073d6e50832a28ddd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::PortableMemInfoBlock::PortableMemInfoBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MemInfoBlock &amp; Block, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a4c0e5dd93f0bc1942fcd93ae8e7a23ea">MemProfSchema</a> &amp; IncomingSchema)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a842e49a58fb3eba4e42a8dadad77745b">llvm::to_underlying</a>.</p>

</div>
</div>

### PortableMemInfoBlock() {#a293a73a87b49b4542c2f82c1b01494a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::PortableMemInfoBlock::PortableMemInfoBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a4c0e5dd93f0bc1942fcd93ae8e7a23ea">MemProfSchema</a> &amp; Schema, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * Ptr)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>References <a href="#a0fe59fa6a9869041f3d4a7628b047ac3">deserialize</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a0bb46cdb00161890b5f1a63cb9278843}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::memprof::PortableMemInfoBlock::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memprof/portablememinfoblock">PortableMemInfoBlock</a> &amp; Other)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>References <a href="#aebf3d98082128980f52ce8192524570b">operator==</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a51b4243ef7b3a6e17d1d2616eea8df84">PortableMemInfoBlock</a>.</p>

</div>
</div>

### operator==() {#aebf3d98082128980f52ce8192524570b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::memprof::PortableMemInfoBlock::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memprof/portablememinfoblock">PortableMemInfoBlock</a> &amp; Other)</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a51b4243ef7b3a6e17d1d2616eea8df84">PortableMemInfoBlock</a>.</p>


<p>Referenced by <a href="#a0bb46cdb00161890b5f1a63cb9278843">operator!=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#ae956e23e4548a0b2cd52be9d60771217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint64_t uint32_t uintptr_t void llvm::memprof::PortableMemInfoBlock::clear ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>Reference <a href="#a51b4243ef7b3a6e17d1d2616eea8df84">PortableMemInfoBlock</a>.</p>

</div>
</div>

### deserialize() {#a0fe59fa6a9869041f3d4a7628b047ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::memprof::PortableMemInfoBlock::deserialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a4c0e5dd93f0bc1942fcd93ae8e7a23ea">MemProfSchema</a> &amp; IncomingSchema, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * Ptr)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#a293a73a87b49b4542c2f82c1b01494a8">PortableMemInfoBlock</a>.</p>

</div>
</div>

### getSchema() {#a79eb2495fa4e516b0a777f71a491fe77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::bitset&lt; llvm::to_underlying(Meta::Size)&gt; llvm::memprof::PortableMemInfoBlock::getSchema ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-2c5234ca03a917e6445ab40c7b8c2ed0/#a7494a112cb5147cd8257cd60f1dc009c">llvm::yaml::CustomMappingTraits&lt; memprof::PortableMemInfoBlock &gt;::output</a>.</p>

</div>
</div>

### MIBEntryDef() {#aae3dcb322e42bb0e0f270af06c45fcf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a16d46a1dad67ea4e7a64523df705682e">AllocCount</a>, <a href="#a16d46a1dad67ea4e7a64523df705682e">AllocCount</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a241d9cbb9abd287496ce9145bf513026}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a5e90d98fea2337722579602a547d180c">MinAccessCount</a>, <a href="#a5e90d98fea2337722579602a547d180c">MinAccessCount</a>, uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a6b7db611cdf455ef0db7398fc17f4e09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a6a2bc58a7513c1ab8cbf51e3415d6851">TotalSize</a>, <a href="#a6a2bc58a7513c1ab8cbf51e3415d6851">TotalSize</a>, uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a2d50e96ce809f6939fdf37e9acbd8376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a25c6f708cd8c864a479f891a831ea888">MaxSize</a>, <a href="#a25c6f708cd8c864a479f891a831ea888">MaxSize</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file MIBEntryDef.inc.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbafe029208a9df98e11b723897a0f19b8d">llvm::memprof::Version3</a>.</p>

</div>
</div>

### MIBEntryDef() {#af43c12a717081ef222676fae6bf27e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#ae80b67790bdda40296ca4c6f92a87a11">DeallocTimestamp</a>, <a href="#ae80b67790bdda40296ca4c6f92a87a11">DeallocTimestamp</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#ac13307a1e83eb1342cd9b4867b2db842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#af2924ec336b30c5c27df1a44f4eb7809">MinLifetime</a>, <a href="#af2924ec336b30c5c27df1a44f4eb7809">MinLifetime</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file MIBEntryDef.inc.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a229923f8cb950f9899eb443578242800">llvm::memprof::MaximumSupportedVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbafe029208a9df98e11b723897a0f19b8d">llvm::memprof::Version3</a>.</p>

</div>
</div>

### MIBEntryDef() {#ac34411958bcccc36073807812f0230ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#af007689fcd73286fb2abcd1d39c4bfcb">AllocCpuId</a>, <a href="#af007689fcd73286fb2abcd1d39c4bfcb">AllocCpuId</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#aa820a27df40941f74e3f8fbc1e7efca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#aba0a772fc9b6a0136a541fde0e536380">NumMigratedCpu</a>, <a href="#aba0a772fc9b6a0136a541fde0e536380">NumMigratedCpu</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a0a49b5403483facaf1acf76a0d997851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#af3156129271b943e3fdd86b0700b58ec">NumSameAllocCpu</a>, <a href="#af3156129271b943e3fdd86b0700b58ec">NumSameAllocCpu</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file MIBEntryDef.inc.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#abee3ddc7c6eb611a3b96fb69489c81caaa6122a65eaa676f700ae68d393054a37">llvm::memprof::Start</a>.</p>

</div>
</div>

### MIBEntryDef() {#adc9d73fe3258e7e306fbb3d44d24f9f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a90450d0f9244f22fd2251e3adf6f0622">DataTypeId</a>, <a href="#a90450d0f9244f22fd2251e3adf6f0622">DataTypeId</a>, uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#aa5acabbbf5962721e242af51b4d005e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a74ffbe21916456f1d3f2cc25b1037479">MinAccessDensity</a>, <a href="#a74ffbe21916456f1d3f2cc25b1037479">MinAccessDensity</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file MIBEntryDef.inc.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### MIBEntryDef() {#a3cd082c17748e8a6983b81e2dc3f174d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a27b66ff857980a3b4164001f7b16507e">TotalLifetimeAccessDensity</a>, <a href="#a27b66ff857980a3b4164001f7b16507e">TotalLifetimeAccessDensity</a>, uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#af63b47eba30f5b44c44fc365ab9ca613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#aa764e9bb29966a2eeb623b182439b966">MaxLifetimeAccessDensity</a>, <a href="#aa764e9bb29966a2eeb623b182439b966">MaxLifetimeAccessDensity</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a01165bba4ba67be1ff76aa478de7721a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#aee68e58fcdbed6070dca830978aeaf27">AccessHistogram</a>, <a href="#aee68e58fcdbed6070dca830978aeaf27">AccessHistogram</a>, uintptr_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a4482fe2436110d9157c42a264135b006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a3c7301eef4644f34b8715023f3d665e3">TotalAccessCount</a>, <a href="#a3c7301eef4644f34b8715023f3d665e3">TotalAccessCount</a>, uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a4bb0fb7a42b5f66f0a4cffbf33ff999e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a0a3d9fafa313c7237f67e90e1c07ece6">MaxAccessCount</a>, <a href="#a0a3d9fafa313c7237f67e90e1c07ece6">MaxAccessCount</a>, uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#ad7ca54aa36c84d9489fefd04fd2afa02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#ad5d7e361735593dd000570a0875f078a">MinSize</a>, <a href="#ad5d7e361735593dd000570a0875f078a">MinSize</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#abfb2013d3e46bba1a42f0dfba612795f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a1b1c7bb733eb271e5724e2195b1363da">AllocTimestamp</a>, <a href="#a1b1c7bb733eb271e5724e2195b1363da">AllocTimestamp</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a25ed396e4204815792c382667f27d4f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a6ddccf17449bdfaf8531484864842837">TotalLifetime</a>, <a href="#a6ddccf17449bdfaf8531484864842837">TotalLifetime</a>, uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#ab3e52367a1ac1b47fed71334f7db38fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#aef4c74c81344ea711dba09e17b361858">MaxLifetime</a>, <a href="#aef4c74c81344ea711dba09e17b361858">MaxLifetime</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a2ca33eb453cce3aebb589cbf249f7439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#aa24623fced1e91c425be64407545a64a">DeallocCpuId</a>, <a href="#aa24623fced1e91c425be64407545a64a">DeallocCpuId</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file MIBEntryDef.inc.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>.</p>

</div>
</div>

### MIBEntryDef() {#a19decb6d90f34308cc44a893db0c84c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a793d215aa9b965406a8e0a3d2af19e4c">NumLifetimeOverlaps</a>, <a href="#a793d215aa9b965406a8e0a3d2af19e4c">NumLifetimeOverlaps</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a9a90c90a746fbb5f3b3e37085bd285ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a39ce04b4cc9a736794fe3d3a9321dece">NumSameDeallocCpu</a>, <a href="#a39ce04b4cc9a736794fe3d3a9321dece">NumSameDeallocCpu</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#ac430de2a945a7102ca202eee0f0ad50a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#af23cd84e74cd9d010997dfe855bea2c2">TotalAccessDensity</a>, <a href="#af23cd84e74cd9d010997dfe855bea2c2">TotalAccessDensity</a>, uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a2eb23a9aece97c0cc4e0f4066bb8d41f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#aef84b4330545b5d4b1185dea238cebdb">MaxAccessDensity</a>, <a href="#aef84b4330545b5d4b1185dea238cebdb">MaxAccessDensity</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a6771ff046d637aaed03100cbae0d069d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint64_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a76f2748c6822dbcd8a361cf05fc666ab">MinLifetimeAccessDensity</a>, <a href="#a76f2748c6822dbcd8a361cf05fc666ab">MinLifetimeAccessDensity</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a1b3cbd3f8cae0d97779e8c1fd78a1207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint64_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a5012ee6358ef6abeb3fa7112eff5ab76">AccessHistogramSize</a>, <a href="#a5012ee6358ef6abeb3fa7112eff5ab76">AccessHistogramSize</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file MIBEntryDef.inc.</p>

</div>
</div>

### printYAML() {#ab4f5f9d64423198132a7679d93dca9d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::memprof::PortableMemInfoBlock::printYAML (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>References <a href="#aee68e58fcdbed6070dca830978aeaf27">AccessHistogram</a>, <a href="#a5012ee6358ef6abeb3fa7112eff5ab76">AccessHistogramSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### serialize() {#acc4d6cca2bd9997078d0dcd72cad45a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::memprof::PortableMemInfoBlock::serialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a4c0e5dd93f0bc1942fcd93ae8e7a23ea">MemProfSchema</a> &amp; Schema, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### MIBEntryDef() {#aae3dcb322e42bb0e0f270af06c45fcf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a16d46a1dad67ea4e7a64523df705682e">AllocCount</a>, <a href="#a16d46a1dad67ea4e7a64523df705682e">AllocCount</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a241d9cbb9abd287496ce9145bf513026}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a5e90d98fea2337722579602a547d180c">MinAccessCount</a>, <a href="#a5e90d98fea2337722579602a547d180c">MinAccessCount</a>, uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a6b7db611cdf455ef0db7398fc17f4e09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a6a2bc58a7513c1ab8cbf51e3415d6851">TotalSize</a>, <a href="#a6a2bc58a7513c1ab8cbf51e3415d6851">TotalSize</a>, uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a2d50e96ce809f6939fdf37e9acbd8376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a25c6f708cd8c864a479f891a831ea888">MaxSize</a>, <a href="#a25c6f708cd8c864a479f891a831ea888">MaxSize</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#af43c12a717081ef222676fae6bf27e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#ae80b67790bdda40296ca4c6f92a87a11">DeallocTimestamp</a>, <a href="#ae80b67790bdda40296ca4c6f92a87a11">DeallocTimestamp</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#ac13307a1e83eb1342cd9b4867b2db842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#af2924ec336b30c5c27df1a44f4eb7809">MinLifetime</a>, <a href="#af2924ec336b30c5c27df1a44f4eb7809">MinLifetime</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#ac34411958bcccc36073807812f0230ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#af007689fcd73286fb2abcd1d39c4bfcb">AllocCpuId</a>, <a href="#af007689fcd73286fb2abcd1d39c4bfcb">AllocCpuId</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#aa820a27df40941f74e3f8fbc1e7efca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#aba0a772fc9b6a0136a541fde0e536380">NumMigratedCpu</a>, <a href="#aba0a772fc9b6a0136a541fde0e536380">NumMigratedCpu</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a0a49b5403483facaf1acf76a0d997851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#af3156129271b943e3fdd86b0700b58ec">NumSameAllocCpu</a>, <a href="#af3156129271b943e3fdd86b0700b58ec">NumSameAllocCpu</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#adc9d73fe3258e7e306fbb3d44d24f9f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a90450d0f9244f22fd2251e3adf6f0622">DataTypeId</a>, <a href="#a90450d0f9244f22fd2251e3adf6f0622">DataTypeId</a>, uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#aa5acabbbf5962721e242af51b4d005e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a74ffbe21916456f1d3f2cc25b1037479">MinAccessDensity</a>, <a href="#a74ffbe21916456f1d3f2cc25b1037479">MinAccessDensity</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#a3cd082c17748e8a6983b81e2dc3f174d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#a27b66ff857980a3b4164001f7b16507e">TotalLifetimeAccessDensity</a>, <a href="#a27b66ff857980a3b4164001f7b16507e">TotalLifetimeAccessDensity</a>, uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file MIBEntryDef.inc.</p>

</div>
</div>

### MIBEntryDef() {#af63b47eba30f5b44c44fc365ab9ca613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MIBEntryDef (<a href="#aa764e9bb29966a2eeb623b182439b966">MaxLifetimeAccessDensity</a>, <a href="#aa764e9bb29966a2eeb623b182439b966">MaxLifetimeAccessDensity</a>, uint32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file MIBEntryDef.inc.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AccessHistogram {#aee68e58fcdbed6070dca830978aeaf27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint64_t uint32_t llvm::memprof::PortableMemInfoBlock::AccessHistogram</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file MIBEntryDef.inc, definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>Referenced by <a href="#ab4f5f9d64423198132a7679d93dca9d7">printYAML</a>.</p>

</div>
</div>

### AccessHistogramSize {#a5012ee6358ef6abeb3fa7112eff5ab76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::AccessHistogramSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file MIBEntryDef.inc, definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>Referenced by <a href="#ab4f5f9d64423198132a7679d93dca9d7">printYAML</a>.</p>

</div>
</div>

### AllocCount {#a16d46a1dad67ea4e7a64523df705682e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::AllocCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file MIBEntryDef.inc, definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### AllocCpuId {#af007689fcd73286fb2abcd1d39c4bfcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::AllocCpuId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file MIBEntryDef.inc, definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### AllocTimestamp {#a1b1c7bb733eb271e5724e2195b1363da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t llvm::memprof::PortableMemInfoBlock::AllocTimestamp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file MIBEntryDef.inc, definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### DataTypeId {#a90450d0f9244f22fd2251e3adf6f0622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::DataTypeId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file MIBEntryDef.inc, definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### DeallocCpuId {#aa24623fced1e91c425be64407545a64a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t llvm::memprof::PortableMemInfoBlock::DeallocCpuId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file MIBEntryDef.inc, definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### DeallocTimestamp {#ae80b67790bdda40296ca4c6f92a87a11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t llvm::memprof::PortableMemInfoBlock::DeallocTimestamp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file MIBEntryDef.inc, definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### MaxAccessCount {#a0a3d9fafa313c7237f67e90e1c07ece6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::memprof::PortableMemInfoBlock::MaxAccessCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file MIBEntryDef.inc, definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### MaxAccessDensity {#aef84b4330545b5d4b1185dea238cebdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t llvm::memprof::PortableMemInfoBlock::MaxAccessDensity</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file MIBEntryDef.inc, definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### MaxLifetime {#aef4c74c81344ea711dba09e17b361858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t llvm::memprof::PortableMemInfoBlock::MaxLifetime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file MIBEntryDef.inc, definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### MaxLifetimeAccessDensity {#aa764e9bb29966a2eeb623b182439b966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint64_t llvm::memprof::PortableMemInfoBlock::MaxLifetimeAccessDensity</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 119 of file MIBEntryDef.inc, definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### MaxSize {#a25c6f708cd8c864a479f891a831ea888}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t llvm::memprof::PortableMemInfoBlock::MaxSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file MIBEntryDef.inc, definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### MinAccessCount {#a5e90d98fea2337722579602a547d180c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MinAccessCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file MIBEntryDef.inc, definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### MinAccessDensity {#a74ffbe21916456f1d3f2cc25b1037479}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t llvm::memprof::PortableMemInfoBlock::MinAccessDensity</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file MIBEntryDef.inc, definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### MinLifetime {#af2924ec336b30c5c27df1a44f4eb7809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::MinLifetime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file MIBEntryDef.inc, definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### MinLifetimeAccessDensity {#a76f2748c6822dbcd8a361cf05fc666ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t llvm::memprof::PortableMemInfoBlock::MinLifetimeAccessDensity</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file MIBEntryDef.inc, definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### MinSize {#ad5d7e361735593dd000570a0875f078a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t llvm::memprof::PortableMemInfoBlock::MinSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file MIBEntryDef.inc, definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### NumLifetimeOverlaps {#a793d215aa9b965406a8e0a3d2af19e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::NumLifetimeOverlaps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file MIBEntryDef.inc, definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### NumMigratedCpu {#aba0a772fc9b6a0136a541fde0e536380}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::NumMigratedCpu</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file MIBEntryDef.inc, definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### NumSameAllocCpu {#af3156129271b943e3fdd86b0700b58ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::NumSameAllocCpu</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file MIBEntryDef.inc, definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### NumSameDeallocCpu {#a39ce04b4cc9a736794fe3d3a9321dece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::NumSameDeallocCpu</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file MIBEntryDef.inc, definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### TotalAccessCount {#a3c7301eef4644f34b8715023f3d665e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::PortableMemInfoBlock::TotalAccessCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file MIBEntryDef.inc, definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### TotalAccessDensity {#af23cd84e74cd9d010997dfe855bea2c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::TotalAccessDensity</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file MIBEntryDef.inc, definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### TotalLifetime {#a6ddccf17449bdfaf8531484864842837}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t llvm::memprof::PortableMemInfoBlock::TotalLifetime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file MIBEntryDef.inc, definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### TotalLifetimeAccessDensity {#a27b66ff857980a3b4164001f7b16507e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint64_t uint32_t uint32_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t llvm::memprof::PortableMemInfoBlock::TotalLifetimeAccessDensity</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file MIBEntryDef.inc, definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

### TotalSize {#a6a2bc58a7513c1ab8cbf51e3415d6851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t uint64_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t uint32_t uint32_t uint32_t uint32_t uint64_t llvm::memprof::PortableMemInfoBlock::TotalSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file MIBEntryDef.inc, definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Schema {#abcd194645d23808a8e179cba21d0e504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::bitset&lt;llvm::to_underlying(Meta::Size)&gt; llvm::memprof::PortableMemInfoBlock::Schema</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### serializedSize() {#a8c040a57b4b47b1a20651b401b367b94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::memprof::PortableMemInfoBlock::serializedSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a4c0e5dd93f0bc1942fcd93ae8e7a23ea">MemProfSchema</a> &amp; Schema)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acaa5a5ff92b2d28c6d06e8c933f6b532">llvm::memprof::deserializeV2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a2ac7af3ec53f7157147c7537fb810e96">llvm::memprof::deserializeV3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a49bcf18527d9a40d5eee1eb44821cbcb">llvm::memprof::serializedSizeV2</a> and <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a5f06862de128b8a111f2ac9183fa2dee">llvm::memprof::serializedSizeV3</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a></li>
<li>MIBEntryDef.inc</li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
