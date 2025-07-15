---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/loongarch
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `LoongArch` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::LoongArch { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loongarch/archinfo">ArchInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loongarch/featureinfo">FeatureInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">FeatureKind : uint32_t { <a href="#a939d69d21a37e26fa57818a35441e284">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ArchKind { <a href="#a985d21e19016be0acc8ca0975923da38">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Fixups { <a href="#a570edf0f57d14f265cdb232c05912442">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed55f5a0ac555b889c11ff633ae1eba">isValidArchName</a> (StringRef Arch)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a409838e230dbdf71fd3a268819adf0fc">getArchFeatures</a> (StringRef Arch, std::vector&lt; StringRef &gt; &amp;Features)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51d5665bd2d5708908ea87e2aef48cf5">isValidCPUName</a> (StringRef TuneCPU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7c8d1932dbd377676019145bc7efa80">fillValidCPUList</a> (SmallVectorImpl&lt; StringRef &gt; &amp;Values)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3542e87c44601a1d8d22b23aab30681b">getDefaultArch</a> (bool Is64Bit)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53f1e18da798927bb536af39e1239530">isSEXT_W</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d9cddc32081aa7e06b9df7f41de248b">FClassMaskSignalingNaN</a> = 0x001</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa97f46d695c8c112c23b5eb3c702f78e">FClassMaskQuietNaN</a> = 0x002</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf06d9523a1e2b27258b6d79650753bd">FClassMaskNegativeInfinity</a> = 0x004</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b0acc9bb7b9804220406803b3af685f">FClassMaskNegativeNormal</a> = 0x008</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3767b4855b15f66c2ab441f173f6dca9">FClassMaskNegativeSubnormal</a> = 0x010</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98264e85aeed721633d76420fc5aff07">FClassMaskNegativeZero</a> = 0x020</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aaf02f8e17a3cc482c0a93845acd02e">FClassMaskPositiveInfinity</a> = 0x040</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3d7ddd3bd2f6ffb1b9ab6675295f96c">FClassMaskPositiveNormal</a> = 0x080</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af959e2432c694caed676cb67a5712715">FClassMaskPositiveSubnormal</a> = 0x100</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af32c99fe79a96944302960d208f3249d">FClassMaskPositiveZero</a> = 0x200</td>
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

## Enumerations

### ArchKind {#a985d21e19016be0acc8ca0975923da38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::LoongArch::ArchKind </td>
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


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/loongarchtargetparser-h">LoongArchTargetParser.h</a>.</p>

</div>
</div>

### FeatureKind {#a939d69d21a37e26fa57818a35441e284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LoongArch::FeatureKind : uint32_t</td>
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
<td class="doxyEnumItemName">FK_64BIT<a id="a939d69d21a37e26fa57818a35441e284afc2b624bdc22be599c8eea536106d50f"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_FP32<a id="a939d69d21a37e26fa57818a35441e284a3b58ee64942aba6f236f142aaaabc3a1"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_FP64<a id="a939d69d21a37e26fa57818a35441e284adb98b5519f9499c9eebf418eb1a938b0"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_LSX<a id="a939d69d21a37e26fa57818a35441e284ad29b78c4b7685957b604801274d82c90"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_LASX<a id="a939d69d21a37e26fa57818a35441e284a0a0c0d82673efc120035d311861245aa"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_LBT<a id="a939d69d21a37e26fa57818a35441e284a9d27f45f7bbddf136d6c71f1ce8f0d62"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_LVZ<a id="a939d69d21a37e26fa57818a35441e284abf4ec94d25682bd8f50f75122438b370"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_UAL<a id="a939d69d21a37e26fa57818a35441e284a4ab3d158dd89af5d8e504ac8dc982866"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_FRECIPE<a id="a939d69d21a37e26fa57818a35441e284ad9770bc4386718969492547eebe6de4f"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_LAM_BH<a id="a939d69d21a37e26fa57818a35441e284ae061875e965f4fe962636a27d2c017a4"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_LAMCAS<a id="a939d69d21a37e26fa57818a35441e284a68dfd1f70d2f792e9a5b6ac41efffd52"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_LD_SEQ_SA<a id="a939d69d21a37e26fa57818a35441e284a5204a9f8cd989eabc8bcf70af3a1e4a1"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_DIV32<a id="a939d69d21a37e26fa57818a35441e284a8d9aa4c2a2316af7646fbcd457de3b41"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_SCQ<a id="a939d69d21a37e26fa57818a35441e284aabe541474a6126b93dd68d0e0f508b16"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 14)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/loongarchtargetparser-h">LoongArchTargetParser.h</a>.</p>

</div>
</div>

### Fixups {#a570edf0f57d14f265cdb232c05912442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LoongArch::Fixups </td>
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
<td class="doxyEnumItemName">fixup_loongarch_b16<a id="a570edf0f57d14f265cdb232c05912442a3f224f26aafd12d872689f8eb64ca9ff"></a></td>
<td class="doxyEnumItemDescription"> (= FirstTargetFixupKind)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_b21<a id="a570edf0f57d14f265cdb232c05912442a6a204b67935b35bfa83298c90529c8a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_b26<a id="a570edf0f57d14f265cdb232c05912442a392f7ae3052bbb64a2fe93f149406d91"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_abs_hi20<a id="a570edf0f57d14f265cdb232c05912442a21687a5a7d599a51082b61a1d0a6460b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_abs_lo12<a id="a570edf0f57d14f265cdb232c05912442a343c4c51960b95f6932cb1ba63ed48cf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_abs64_lo20<a id="a570edf0f57d14f265cdb232c05912442a5781daab526ee6f78c11cef621710a2d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_abs64_hi12<a id="a570edf0f57d14f265cdb232c05912442a182008c1f6c332cb2cfd8c3d3ffada3e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_le_hi20<a id="a570edf0f57d14f265cdb232c05912442ada76942b1c8dba41d75a85b4fc7c5008"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_le_lo12<a id="a570edf0f57d14f265cdb232c05912442a212dc9b5723f913647b5fdfede3f81d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_le64_lo20<a id="a570edf0f57d14f265cdb232c05912442a814739c18efc36fceba5e291301c7c68"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_le64_hi12<a id="a570edf0f57d14f265cdb232c05912442a70bee6eb9030175a97edc63e692efdf1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_invalid<a id="a570edf0f57d14f265cdb232c05912442a3ec696ff217c26a3f7cdc6cde57036be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumTargetFixupKinds<a id="a570edf0f57d14f265cdb232c05912442af19a193fa0d48acd243ddf3078739c25"></a></td>
<td class="doxyEnumItemDescription"> (= fixup_loongarch_invalid - FirstTargetFixupKind)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_pcala_hi20<a id="a570edf0f57d14f265cdb232c05912442a30f70c1a75b3d1f90a90bad77d1f9552"></a></td>
<td class="doxyEnumItemDescription">
 (=
      FirstLiteralRelocationKind + ELF::R_LARCH_PCALA_HI20)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_pcala_lo12<a id="a570edf0f57d14f265cdb232c05912442aaacb6594915668631b88a1a9dd82a1a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_pcala64_lo20<a id="a570edf0f57d14f265cdb232c05912442a598695ee31d24c927a625ba43991764b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_pcala64_hi12<a id="a570edf0f57d14f265cdb232c05912442a2629a2a4eda3b73a2194529d8c62a01f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_got_pc_hi20<a id="a570edf0f57d14f265cdb232c05912442ace2a6b39eee23db158b0de4cbd417a0d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_got_pc_lo12<a id="a570edf0f57d14f265cdb232c05912442a84ae204828658f7a4ddb6d3d2aef7d9d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_got64_pc_lo20<a id="a570edf0f57d14f265cdb232c05912442a816bc68679fd92ee1d3bc24d616734b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_got64_pc_hi12<a id="a570edf0f57d14f265cdb232c05912442a4e73d9c87b6ea7808c96d97684a5921e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_got_hi20<a id="a570edf0f57d14f265cdb232c05912442ad9c7cbe9f5b23dc2c8573bb0eb65281c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_got_lo12<a id="a570edf0f57d14f265cdb232c05912442aacce8aaa2283b7aab1c717c12737b55c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_got64_lo20<a id="a570edf0f57d14f265cdb232c05912442a76186316b79421b904e5616dd40a77f4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_got64_hi12<a id="a570edf0f57d14f265cdb232c05912442a27effc7fabddb827c97fe12c08b4b4ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_ie_pc_hi20<a id="a570edf0f57d14f265cdb232c05912442aff8b5461923257f1d8082bb3ee4a3900"></a></td>
<td class="doxyEnumItemDescription">
 (=
      FirstLiteralRelocationKind + ELF::R_LARCH_TLS_IE_PC_HI20)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_ie_pc_lo12<a id="a570edf0f57d14f265cdb232c05912442a2f5a1b60ab4716802c2f13dc01bbddc2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_ie64_pc_lo20<a id="a570edf0f57d14f265cdb232c05912442ad0dddc75ccc9b5194ec36fc1d694c578"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_ie64_pc_hi12<a id="a570edf0f57d14f265cdb232c05912442aca0d1ed529bed5ad80294b4464a6788b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_ie_hi20<a id="a570edf0f57d14f265cdb232c05912442a25a46a6951286c5aba59fbe61a330d3f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_ie_lo12<a id="a570edf0f57d14f265cdb232c05912442a18f18ff993ffd17a6d47f8918dd438e4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_ie64_lo20<a id="a570edf0f57d14f265cdb232c05912442adf22d94f89325c70d09b96b5d876724d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_ie64_hi12<a id="a570edf0f57d14f265cdb232c05912442ae25636abc93c8f21a22e8663f0f3829e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_ld_pc_hi20<a id="a570edf0f57d14f265cdb232c05912442a0bc4de676222971fe2f939c4793c52ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_ld_hi20<a id="a570edf0f57d14f265cdb232c05912442aaa8a760d2c964e5fdab184eb7d1d4181"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_gd_pc_hi20<a id="a570edf0f57d14f265cdb232c05912442a8cc1177a4f234ac06143b5e5f071d570"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_gd_hi20<a id="a570edf0f57d14f265cdb232c05912442a277e092845e4152ebaca04dff5c1b1f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_relax<a id="a570edf0f57d14f265cdb232c05912442a5fca7ef96b80eeb5fd1b6a3163efa7c8"></a></td>
<td class="doxyEnumItemDescription"> (= FirstLiteralRelocationKind + ELF::R_LARCH_RELAX)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_align<a id="a570edf0f57d14f265cdb232c05912442a9d130b671018dac821419a19179b48fa"></a></td>
<td class="doxyEnumItemDescription"> (= FirstLiteralRelocationKind + ELF::R_LARCH_ALIGN)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_pcrel20_s2<a id="a570edf0f57d14f265cdb232c05912442aa97ef6bb067a0826e482475f0d2c58c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_call36<a id="a570edf0f57d14f265cdb232c05912442a59970f56c58d60df377c56b5e91a0bdc"></a></td>
<td class="doxyEnumItemDescription"> (= FirstLiteralRelocationKind + ELF::R_LARCH_CALL36)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_desc_pc_hi20<a id="a570edf0f57d14f265cdb232c05912442ab93d415801aac281c02a45251b7afd2c"></a></td>
<td class="doxyEnumItemDescription">
 (=
      FirstLiteralRelocationKind + ELF::R_LARCH_TLS_DESC_PC_HI20)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_desc_pc_lo12<a id="a570edf0f57d14f265cdb232c05912442af9c08e61060803ae06cfdef3ee6539e1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_desc64_pc_lo20<a id="a570edf0f57d14f265cdb232c05912442a0b331a509be207369a4345fdb7570e5d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_desc64_pc_hi12<a id="a570edf0f57d14f265cdb232c05912442aa95aaec8bb8dad453efc686fda1867b6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_desc_hi20<a id="a570edf0f57d14f265cdb232c05912442a5cfe57ceb00f912383559bcf32db7acf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_desc_lo12<a id="a570edf0f57d14f265cdb232c05912442a9ba95db567e06dacb0dc7942d2e83f93"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_desc64_lo20<a id="a570edf0f57d14f265cdb232c05912442a44def7e9e81969a7cdaa063b216b255b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_desc64_hi12<a id="a570edf0f57d14f265cdb232c05912442a29ef5f049dc0156695b4612536454b75"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_desc_ld<a id="a570edf0f57d14f265cdb232c05912442a90e25d7d9eab9d83d73eaae639e3efc9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_desc_call<a id="a570edf0f57d14f265cdb232c05912442a836a1f04695534ec8427ce5fa2dd23ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_le_hi20_r<a id="a570edf0f57d14f265cdb232c05912442aef434a0aa4c47da8b4fea92d745ad4da"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_le_add_r<a id="a570edf0f57d14f265cdb232c05912442a2b7b0cf591b58d1f5b6e12555947ca8f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_le_lo12_r<a id="a570edf0f57d14f265cdb232c05912442a4c552db3ca835a6d0f5777810e8371d2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_ld_pcrel20_s2<a id="a570edf0f57d14f265cdb232c05912442ac5ba68eb7f333ccda09e3f458b8d2b8c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_gd_pcrel20_s2<a id="a570edf0f57d14f265cdb232c05912442a8767028752c41efd2842421e1dce2bae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_loongarch_tls_desc_pcrel20_s2<a id="a570edf0f57d14f265cdb232c05912442a0bc1b42c2d43687b84f88de20cb7c28a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchfixupkinds-h">LoongArchFixupKinds.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### fillValidCPUList() {#af7c8d1932dbd377676019145bc7efa80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoongArch::fillValidCPUList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; Values)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/loongarchtargetparser-h">LoongArchTargetParser.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/loongarchtargetparser-cpp">LoongArchTargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/loongarchtargetparser-cpp/#ad78bd80a2904c84003183a2a34356a60">AllArchs</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>.</p>

</div>
</div>

### getArchFeatures() {#a409838e230dbdf71fd3a268819adf0fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoongArch::getArchFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Arch, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; Features)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/loongarchtargetparser-h">LoongArchTargetParser.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/loongarchtargetparser-cpp">LoongArchTargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/loongarchtargetparser-cpp/#ad78bd80a2904c84003183a2a34356a60">AllArchs</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/loongarchtargetparser-cpp/#aacf0aaeeb21e1630ab574012e090e8c0">AllFeatures</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### getDefaultArch() {#a3542e87c44601a1d8d22b23aab30681b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::LoongArch::getDefaultArch (bool Is64Bit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/loongarchtargetparser-h">LoongArchTargetParser.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/loongarchtargetparser-cpp">LoongArchTargetParser.cpp</a>.</p>

</div>
</div>

### isSEXT\_W() {#a53f1e18da798927bb536af39e1239530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoongArch::isSEXT_W (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-h">LoongArchInstrInfo.h</a>, definition at line 760 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-cpp">LoongArchInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loongarchoptwinstrs-cpp-/loongarchoptwinstrs/#ae09cb58043419f65afe846062e100977">anonymous{LoongArchOptWInstrs.cpp}::LoongArchOptWInstrs::removeSExtWInstrs</a>.</p>

</div>
</div>

### isValidArchName() {#a9ed55f5a0ac555b889c11ff633ae1eba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoongArch::isValidArchName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Arch)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/loongarchtargetparser-h">LoongArchTargetParser.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/loongarchtargetparser-cpp">LoongArchTargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/targetparser/loongarchtargetparser-cpp/#ad78bd80a2904c84003183a2a34356a60">AllArchs</a>.</p>


<p>Referenced by <a href="#a51d5665bd2d5708908ea87e2aef48cf5">isValidCPUName</a>.</p>

</div>
</div>

### isValidCPUName() {#a51d5665bd2d5708908ea87e2aef48cf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoongArch::isValidCPUName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/loongarchtargetparser-h">LoongArchTargetParser.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/loongarchtargetparser-cpp">LoongArchTargetParser.cpp</a>.</p>


<p>Reference <a href="#a9ed55f5a0ac555b889c11ff633ae1eba">isValidArchName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### FClassMaskNegativeInfinity {#aaf06d9523a1e2b27258b6d79650753bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoongArch::FClassMaskNegativeInfinity = 0x004</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-h">LoongArchInstrInfo.h</a>.</p>

</div>
</div>

### FClassMaskNegativeNormal {#a9b0acc9bb7b9804220406803b3af685f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoongArch::FClassMaskNegativeNormal = 0x008</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-h">LoongArchInstrInfo.h</a>.</p>

</div>
</div>

### FClassMaskNegativeSubnormal {#a3767b4855b15f66c2ab441f173f6dca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoongArch::FClassMaskNegativeSubnormal = 0x010</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-h">LoongArchInstrInfo.h</a>.</p>

</div>
</div>

### FClassMaskNegativeZero {#a98264e85aeed721633d76420fc5aff07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoongArch::FClassMaskNegativeZero = 0x020</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-h">LoongArchInstrInfo.h</a>.</p>

</div>
</div>

### FClassMaskPositiveInfinity {#a7aaf02f8e17a3cc482c0a93845acd02e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoongArch::FClassMaskPositiveInfinity = 0x040</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-h">LoongArchInstrInfo.h</a>.</p>

</div>
</div>

### FClassMaskPositiveNormal {#ae3d7ddd3bd2f6ffb1b9ab6675295f96c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoongArch::FClassMaskPositiveNormal = 0x080</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-h">LoongArchInstrInfo.h</a>.</p>

</div>
</div>

### FClassMaskPositiveSubnormal {#af959e2432c694caed676cb67a5712715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoongArch::FClassMaskPositiveSubnormal = 0x100</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-h">LoongArchInstrInfo.h</a>.</p>

</div>
</div>

### FClassMaskPositiveZero {#af32c99fe79a96944302960d208f3249d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoongArch::FClassMaskPositiveZero = 0x200</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-h">LoongArchInstrInfo.h</a>.</p>

</div>
</div>

### FClassMaskQuietNaN {#aa97f46d695c8c112c23b5eb3c702f78e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoongArch::FClassMaskQuietNaN = 0x002</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-h">LoongArchInstrInfo.h</a>.</p>

</div>
</div>

### FClassMaskSignalingNaN {#a1d9cddc32081aa7e06b9df7f41de248b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoongArch::FClassMaskSignalingNaN = 0x001</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-h">LoongArchInstrInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/loongarchtargetparser-h">LoongArchTargetParser.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-cpp">LoongArchInstrInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-h">LoongArchInstrInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchfixupkinds-h">LoongArchFixupKinds.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/targetparser/loongarchtargetparser-cpp">LoongArchTargetParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
