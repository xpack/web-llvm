---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-mcdwarf-cpp-/ciekey
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CIEKey` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{MCDwarf.cpp}::CIEKey { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f4530e687721a265d42900c9cd144ce">CIEKey</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9358392b0d745a5a5eddaf69ea6cd715">CIEKey</a> (const MCDwarfFrameInfo &amp;Frame)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a789fd2c563375da6ad44569278f18f28">operator&lt;</a> (const CIEKey &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f3106927442141f9d2352d07ba85bf">operator==</a> (const CIEKey &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd89a0ce54d381f9d42c001c2f1b9eba">operator!=</a> (const CIEKey &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab04db57c85b2a310784159bb13b31f0d">PersonalityName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a858e04751fe4c3e60cb9ba2d3a6a7b02">Personality</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad143d943b928152bc6c54c3d86e66ae2">PersonalityEncoding</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3865f796500b5dd59fc3ecee977d6b4b">LsdaEncoding</a> = -1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a288bdf4da4cf0e7a3d8899b9ffb0e233">IsSignalFrame</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7329f4ed1f69db89cd79c99079acc5bf">IsSimple</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc23b204f8472b5499814697d30462df">RAReg</a> = static_cast&lt;unsigned&gt;(UINT_MAX)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a82ead841ac1cd4a06bf22108a23246">IsBKeyFrame</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7103d50e16d566198456fe69932c16cc">IsMTETaggedFrame</a> = false</td>
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


<p>Definition at line 1832 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CIEKey() {#a4f4530e687721a265d42900c9cd144ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MCDwarf.cpp}::CIEKey::CIEKey ()</td>
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



<p>Definition at line 1833 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Referenced by <a href="#acd89a0ce54d381f9d42c001c2f1b9eba">operator!=</a>, <a href="#a789fd2c563375da6ad44569278f18f28">operator&lt;</a> and <a href="#ad1f3106927442141f9d2352d07ba85bf">operator==</a>.</p>

</div>
</div>

### CIEKey() {#a9358392b0d745a5a5eddaf69ea6cd715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MCDwarf.cpp}::CIEKey::CIEKey (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo">MCDwarfFrameInfo</a> &amp; Frame)</td>
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



<p>Definition at line 1835 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="#a6a82ead841ac1cd4a06bf22108a23246">IsBKeyFrame</a>, <a href="#a7103d50e16d566198456fe69932c16cc">IsMTETaggedFrame</a>, <a href="#a288bdf4da4cf0e7a3d8899b9ffb0e233">IsSignalFrame</a>, <a href="#a7329f4ed1f69db89cd79c99079acc5bf">IsSimple</a>, <a href="#a3865f796500b5dd59fc3ecee977d6b4b">LsdaEncoding</a>, <a href="#a858e04751fe4c3e60cb9ba2d3a6a7b02">Personality</a>, <a href="#ad143d943b928152bc6c54c3d86e66ae2">PersonalityEncoding</a> and <a href="#afc23b204f8472b5499814697d30462df">RAReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#acd89a0ce54d381f9d42c001c2f1b9eba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MCDwarf.cpp}::CIEKey::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-mcdwarf-cpp-/ciekey">CIEKey</a> &amp; Other)</td>
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



<p>Definition at line 1867 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="#a4f4530e687721a265d42900c9cd144ce">CIEKey</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator&lt;() {#a789fd2c563375da6ad44569278f18f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MCDwarf.cpp}::CIEKey::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-mcdwarf-cpp-/ciekey">CIEKey</a> &amp; Other)</td>
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



<p>Definition at line 1849 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="#a4f4530e687721a265d42900c9cd144ce">CIEKey</a>, <a href="#a6a82ead841ac1cd4a06bf22108a23246">IsBKeyFrame</a>, <a href="#a7103d50e16d566198456fe69932c16cc">IsMTETaggedFrame</a>, <a href="#a288bdf4da4cf0e7a3d8899b9ffb0e233">IsSignalFrame</a>, <a href="#a7329f4ed1f69db89cd79c99079acc5bf">IsSimple</a>, <a href="#a3865f796500b5dd59fc3ecee977d6b4b">LsdaEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#ad143d943b928152bc6c54c3d86e66ae2">PersonalityEncoding</a>, <a href="#ab04db57c85b2a310784159bb13b31f0d">PersonalityName</a> and <a href="#afc23b204f8472b5499814697d30462df">RAReg</a>.</p>

</div>
</div>

### operator==() {#ad1f3106927442141f9d2352d07ba85bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MCDwarf.cpp}::CIEKey::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-mcdwarf-cpp-/ciekey">CIEKey</a> &amp; Other)</td>
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



<p>Definition at line 1859 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="#a4f4530e687721a265d42900c9cd144ce">CIEKey</a>, <a href="#a6a82ead841ac1cd4a06bf22108a23246">IsBKeyFrame</a>, <a href="#a7103d50e16d566198456fe69932c16cc">IsMTETaggedFrame</a>, <a href="#a288bdf4da4cf0e7a3d8899b9ffb0e233">IsSignalFrame</a>, <a href="#a7329f4ed1f69db89cd79c99079acc5bf">IsSimple</a>, <a href="#a3865f796500b5dd59fc3ecee977d6b4b">LsdaEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a858e04751fe4c3e60cb9ba2d3a6a7b02">Personality</a>, <a href="#ad143d943b928152bc6c54c3d86e66ae2">PersonalityEncoding</a> and <a href="#afc23b204f8472b5499814697d30462df">RAReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### PersonalityName() {#ab04db57c85b2a310784159bb13b31f0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{MCDwarf.cpp}::CIEKey::PersonalityName ()</td>
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



<p>Definition at line 1843 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Reference <a href="#a858e04751fe4c3e60cb9ba2d3a6a7b02">Personality</a>.</p>


<p>Referenced by <a href="#a789fd2c563375da6ad44569278f18f28">operator&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsBKeyFrame {#a6a82ead841ac1cd4a06bf22108a23246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MCDwarf.cpp}::CIEKey::IsBKeyFrame = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1875 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Referenced by <a href="#a9358392b0d745a5a5eddaf69ea6cd715">CIEKey</a>, <a href="#a789fd2c563375da6ad44569278f18f28">operator&lt;</a> and <a href="#ad1f3106927442141f9d2352d07ba85bf">operator==</a>.</p>

</div>
</div>

### IsMTETaggedFrame {#a7103d50e16d566198456fe69932c16cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MCDwarf.cpp}::CIEKey::IsMTETaggedFrame = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1876 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Referenced by <a href="#a9358392b0d745a5a5eddaf69ea6cd715">CIEKey</a>, <a href="#a789fd2c563375da6ad44569278f18f28">operator&lt;</a> and <a href="#ad1f3106927442141f9d2352d07ba85bf">operator==</a>.</p>

</div>
</div>

### IsSignalFrame {#a288bdf4da4cf0e7a3d8899b9ffb0e233}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MCDwarf.cpp}::CIEKey::IsSignalFrame = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1872 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Referenced by <a href="#a9358392b0d745a5a5eddaf69ea6cd715">CIEKey</a>, <a href="#a789fd2c563375da6ad44569278f18f28">operator&lt;</a> and <a href="#ad1f3106927442141f9d2352d07ba85bf">operator==</a>.</p>

</div>
</div>

### IsSimple {#a7329f4ed1f69db89cd79c99079acc5bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MCDwarf.cpp}::CIEKey::IsSimple = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1873 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Referenced by <a href="#a9358392b0d745a5a5eddaf69ea6cd715">CIEKey</a>, <a href="#a789fd2c563375da6ad44569278f18f28">operator&lt;</a> and <a href="#ad1f3106927442141f9d2352d07ba85bf">operator==</a>.</p>

</div>
</div>

### LsdaEncoding {#a3865f796500b5dd59fc3ecee977d6b4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MCDwarf.cpp}::CIEKey::LsdaEncoding = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1871 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Referenced by <a href="#a9358392b0d745a5a5eddaf69ea6cd715">CIEKey</a>, <a href="#a789fd2c563375da6ad44569278f18f28">operator&lt;</a> and <a href="#ad1f3106927442141f9d2352d07ba85bf">operator==</a>.</p>

</div>
</div>

### Personality {#a858e04751fe4c3e60cb9ba2d3a6a7b02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol* anonymous{MCDwarf.cpp}::CIEKey::Personality = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1869 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Referenced by <a href="#a9358392b0d745a5a5eddaf69ea6cd715">CIEKey</a>, <a href="#ad1f3106927442141f9d2352d07ba85bf">operator==</a> and <a href="#ab04db57c85b2a310784159bb13b31f0d">PersonalityName</a>.</p>

</div>
</div>

### PersonalityEncoding {#ad143d943b928152bc6c54c3d86e66ae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MCDwarf.cpp}::CIEKey::PersonalityEncoding = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1870 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Referenced by <a href="#a9358392b0d745a5a5eddaf69ea6cd715">CIEKey</a>, <a href="#a789fd2c563375da6ad44569278f18f28">operator&lt;</a> and <a href="#ad1f3106927442141f9d2352d07ba85bf">operator==</a>.</p>

</div>
</div>

### RAReg {#afc23b204f8472b5499814697d30462df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MCDwarf.cpp}::CIEKey::RAReg = static_cast&lt;unsigned&gt;(UINT_MAX)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1874 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Referenced by <a href="#a9358392b0d745a5a5eddaf69ea6cd715">CIEKey</a>, <a href="#a789fd2c563375da6ad44569278f18f28">operator&lt;</a> and <a href="#ad1f3106927442141f9d2352d07ba85bf">operator==</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
