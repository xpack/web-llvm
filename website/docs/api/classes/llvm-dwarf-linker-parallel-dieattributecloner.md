---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/dieattributecloner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DIEAttributeCloner` Class Reference

<p>This class creates clones of input <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> attributes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::DIEAttributeCloner { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DWARFLinker/Parallel/DIEAttributeCloner.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66eb90e2a122d1694832a1718a6e3510">DIEAttributeCloner</a> (DIE *OutDIE, CompileUnit &amp;InUnit, CompileUnit *OutUnit, const DWARFDebugInfoEntry *InputDieEntry, DIEGenerator &amp;Generator, std::optional&lt; int64_t &gt; FuncAddressAdjustment, std::optional&lt; int64_t &gt; VarAddressAdjustment, bool HasLocationExpressionAddress)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af97b9a61c488c6624b087784fe2a5122">DIEAttributeCloner</a> (DIE *OutDIE, CompileUnit &amp;InUnit, TypeUnit *OutUnit, const DWARFDebugInfoEntry *InputDieEntry, DIEGenerator &amp;Generator, std::optional&lt; int64_t &gt; FuncAddressAdjustment, std::optional&lt; int64_t &gt; VarAddressAdjustment, bool HasLocationExpressionAddress)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80a2ac72206c04fe2cb7714b513b95dd">DIEAttributeCloner</a> (DIE *OutDIE, CompileUnit &amp;InUnit, CompileUnit::OutputUnitVariantPtr OutUnit, const DWARFDebugInfoEntry *InputDieEntry, DIEGenerator &amp;Generator, std::optional&lt; int64_t &gt; FuncAddressAdjustment, std::optional&lt; int64_t &gt; VarAddressAdjustment, bool HasLocationExpressionAddress)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone attributes of input <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a601419af5c3f8b56909c01a8596aecb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fac38670ec896a95b399e4a82786291">finalizeAbbreviations</a> (bool HasChildrenToClone)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create abbreviations for the output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> after all attributes are cloned. <a href="#a2fac38670ec896a95b399e4a82786291">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37d2788fbc0de7474c370f4107595b50">getOutOffset</a> ()</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77e10b3b8f2ee1990c6ea01fb817526c">cloneStringAttr</a> (const DWARFFormValue &amp;Val, const DWARFAbbreviationDeclaration::AttributeSpec &amp;AttrSpec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone string attribute. <a href="#a77e10b3b8f2ee1990c6ea01fb817526c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62035c942faa72252459166166847bff">cloneDieRefAttr</a> (const DWARFFormValue &amp;Val, const DWARFAbbreviationDeclaration::AttributeSpec &amp;AttrSpec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone attribute referencing another <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a62035c942faa72252459166166847bff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46b9ec0a91b5f1a1ea42559b16bcdc4d">cloneScalarAttr</a> (const DWARFFormValue &amp;Val, const DWARFAbbreviationDeclaration::AttributeSpec &amp;AttrSpec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone scalar attribute. <a href="#a46b9ec0a91b5f1a1ea42559b16bcdc4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00f85301e155c37fcab125f50a67cfb4">cloneBlockAttr</a> (const DWARFFormValue &amp;Val, const DWARFAbbreviationDeclaration::AttributeSpec &amp;AttrSpec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone block or exprloc attribute. <a href="#a00f85301e155c37fcab125f50a67cfb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba2b0348c09eb9e1b9245a012aab2503">cloneAddressAttr</a> (const DWARFFormValue &amp;Val, const DWARFAbbreviationDeclaration::AttributeSpec &amp;AttrSpec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone address attribute. <a href="#aba2b0348c09eb9e1b9245a012aab2503">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a689c387664c7bbe7acdf44a5bb4d47ec">shouldSkipAttribute</a> (DWARFAbbreviationDeclaration::AttributeSpec AttrSpec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if attribute should be skipped. <a href="#a689c387664c7bbe7acdf44a5bb4d47ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/attributesinfo">AttributesInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a088d2a29666b318b459ebcbd96ee1d5c">AttrInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cannot be used concurrently. <a href="#a088d2a29666b318b459ebcbd96ee1d5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8e326dcecfa5386350eb28a2f7aef49">OutDIE</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#ae8e326dcecfa5386350eb28a2f7aef49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ef0e422c431e97a439e9041c06c9caf">InUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/input">Input</a> compilation unit. <a href="#a0ef0e422c431e97a439e9041c06c9caf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/outputunitvariantptr">CompileUnit::OutputUnitVariantPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7025b300d22532590ed8d39dd2f9f37">OutUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Output unit(either "plain" compilation unit, either artificial type unit). <a href="#ab7025b300d22532590ed8d39dd2f9f37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bfcd90fb03cb9b0f0c72103391e936b">DebugInfoOutputSection</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.debug_info section descriptor. <a href="#a1bfcd90fb03cb9b0f0c72103391e936b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ecc8aaf62d09e944d05a9c4e05e908e">InputDieEntry</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/input">Input</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> entry. <a href="#a8ecc8aaf62d09e944d05a9c4e05e908e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abecbbd533de7c6ddd95ecb684e426d60">InputDIEIdx</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/input">Input</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> index. <a href="#abecbbd533de7c6ddd95ecb684e426d60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/diegenerator">DIEGenerator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cffaa8f53fe7ada3bb67e3d5bd1601e">Generator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> generator. <a href="#a3cffaa8f53fe7ada3bb67e3d5bd1601e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa01fc91b9ebc371159da3ccad8f09f56">FuncAddressAdjustment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Relocation adjustment for the function address ranges. <a href="#aa01fc91b9ebc371159da3ccad8f09f56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2c034842b86e727cabd95686828fc5d">VarAddressAdjustment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Relocation adjustment for the variable locations. <a href="#ae2c034842b86e727cabd95686828fc5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1998c4c5f557be9d1e4b4b6d51fc437c">HasLocationExpressionAddress</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates whether InputDieEntry has an location attribute containg address expression. <a href="#a1998c4c5f557be9d1e4b4b6d51fc437c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a349ad92c804dcea3e5f1470bc7dc254f">AttrOutOffset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Output offset after all attributes. <a href="#a349ad92c804dcea3e5f1470bc7dc254f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ad2dde002b59709a633439269e84fb29c">OffsetsPtrVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b1fff9a8fad2b78ec60ff06dfe36db9">PatchesOffsets</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Patches for the cloned attributes. <a href="#a4b1fff9a8fad2b78ec60ff06dfe36db9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb840d515852065f5697378af677962a">Use_DW_FORM_strp</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This flag forces using DW_FORM_strp for string attributes. <a href="#aeb840d515852065f5697378af677962a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class creates clones of input <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> attributes.</p>


<p>It enumerates attributes of input <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>, creates clone for each attribute, adds cloned attribute to the output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DIEAttributeCloner() {#a66eb90e2a122d1694832a1718a6e3510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::DIEAttributeCloner::DIEAttributeCloner (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * OutDIE, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp; InUnit, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> * OutUnit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * InputDieEntry, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/diegenerator">DIEGenerator</a> &amp; Generator, std::optional&lt; int64_t &gt; FuncAddressAdjustment, std::optional&lt; int64_t &gt; VarAddressAdjustment, bool HasLocationExpressionAddress)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>References <a href="#a66eb90e2a122d1694832a1718a6e3510">DIEAttributeCloner</a>, <a href="#aa01fc91b9ebc371159da3ccad8f09f56">FuncAddressAdjustment</a>, <a href="#a3cffaa8f53fe7ada3bb67e3d5bd1601e">Generator</a>, <a href="#a1998c4c5f557be9d1e4b4b6d51fc437c">HasLocationExpressionAddress</a>, <a href="#a8ecc8aaf62d09e944d05a9c4e05e908e">InputDieEntry</a>, <a href="#a0ef0e422c431e97a439e9041c06c9caf">InUnit</a>, <a href="#ae8e326dcecfa5386350eb28a2f7aef49">OutDIE</a>, <a href="#ab7025b300d22532590ed8d39dd2f9f37">OutUnit</a> and <a href="#ae2c034842b86e727cabd95686828fc5d">VarAddressAdjustment</a>.</p>


<p>Referenced by <a href="#a66eb90e2a122d1694832a1718a6e3510">DIEAttributeCloner</a> and <a href="#af97b9a61c488c6624b087784fe2a5122">DIEAttributeCloner</a>.</p>

</div>
</div>

### DIEAttributeCloner() {#af97b9a61c488c6624b087784fe2a5122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::DIEAttributeCloner::DIEAttributeCloner (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * OutDIE, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp; InUnit, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit">TypeUnit</a> * OutUnit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * InputDieEntry, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/diegenerator">DIEGenerator</a> &amp; Generator, std::optional&lt; int64_t &gt; FuncAddressAdjustment, std::optional&lt; int64_t &gt; VarAddressAdjustment, bool HasLocationExpressionAddress)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>References <a href="#a66eb90e2a122d1694832a1718a6e3510">DIEAttributeCloner</a>, <a href="#aa01fc91b9ebc371159da3ccad8f09f56">FuncAddressAdjustment</a>, <a href="#a3cffaa8f53fe7ada3bb67e3d5bd1601e">Generator</a>, <a href="#a1998c4c5f557be9d1e4b4b6d51fc437c">HasLocationExpressionAddress</a>, <a href="#a8ecc8aaf62d09e944d05a9c4e05e908e">InputDieEntry</a>, <a href="#a0ef0e422c431e97a439e9041c06c9caf">InUnit</a>, <a href="#ae8e326dcecfa5386350eb28a2f7aef49">OutDIE</a>, <a href="#ab7025b300d22532590ed8d39dd2f9f37">OutUnit</a> and <a href="#ae2c034842b86e727cabd95686828fc5d">VarAddressAdjustment</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### DIEAttributeCloner() {#a80a2ac72206c04fe2cb7714b513b95dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::DIEAttributeCloner::DIEAttributeCloner (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * OutDIE, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp; InUnit, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/outputunitvariantptr">CompileUnit::OutputUnitVariantPtr</a> OutUnit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * InputDieEntry, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/diegenerator">DIEGenerator</a> &amp; Generator, std::optional&lt; int64_t &gt; FuncAddressAdjustment, std::optional&lt; int64_t &gt; VarAddressAdjustment, bool HasLocationExpressionAddress)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af6f6931771db95a6bffec131b856bd50">llvm::dwarf_linker::DebugInfo</a>, <a href="#a1bfcd90fb03cb9b0f0c72103391e936b">DebugInfoOutputSection</a>, <a href="#aa01fc91b9ebc371159da3ccad8f09f56">FuncAddressAdjustment</a>, <a href="#a3cffaa8f53fe7ada3bb67e3d5bd1601e">Generator</a>, <a href="#a1998c4c5f557be9d1e4b4b6d51fc437c">HasLocationExpressionAddress</a>, <a href="#a8ecc8aaf62d09e944d05a9c4e05e908e">InputDieEntry</a>, <a href="#abecbbd533de7c6ddd95ecb684e426d60">InputDIEIdx</a>, <a href="#a0ef0e422c431e97a439e9041c06c9caf">InUnit</a>, <a href="#ae8e326dcecfa5386350eb28a2f7aef49">OutDIE</a>, <a href="#ab7025b300d22532590ed8d39dd2f9f37">OutUnit</a>, <a href="#aeb840d515852065f5697378af677962a">Use_DW_FORM_strp</a> and <a href="#ae2c034842b86e727cabd95686828fc5d">VarAddressAdjustment</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#a601419af5c3f8b56909c01a8596aecb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEAttributeCloner::clone ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone attributes of input <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>, definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-cpp">DIEAttributeCloner.cpp</a>.</p>


<p>References <a href="#a088d2a29666b318b459ebcbd96ee1d5c">AttrInfo</a>, <a href="#a349ad92c804dcea3e5f1470bc7dc254f">AttrOutOffset</a>, <a href="#aba2b0348c09eb9e1b9245a012aab2503">cloneAddressAttr</a>, <a href="#a00f85301e155c37fcab125f50a67cfb4">cloneBlockAttr</a>, <a href="#a62035c942faa72252459166166847bff">cloneDieRefAttr</a>, <a href="#a46b9ec0a91b5f1a1ea42559b16bcdc4d">cloneScalarAttr</a>, <a href="#a77e10b3b8f2ee1990c6ea01fb817526c">cloneStringAttr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a1bfcd90fb03cb9b0f0c72103391e936b">DebugInfoOutputSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24aff29b8418c7593f015431386cf40b181">llvm::dwarf_linker::DebugStrOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#aa146755e2500aea560c4417a30c0b96b">llvm::DWARFFormValue::extractValue</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga4863132f9f3dd24b6df4cfc6c9cfb676">llvm::dwarf::FormEncodingString</a>, <a href="#a3cffaa8f53fe7ada3bb67e3d5bd1601e">Generator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa02a1d8fb0f561ab81f4a2570db7dc28">llvm::getULEB128Size</a>, <a href="#a8ecc8aaf62d09e944d05a9c4e05e908e">InputDieEntry</a>, <a href="#abecbbd533de7c6ddd95ecb684e426d60">InputDIEIdx</a>, <a href="#a0ef0e422c431e97a439e9041c06c9caf">InUnit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#ae8e326dcecfa5386350eb28a2f7aef49">OutDIE</a>, <a href="#ab7025b300d22532590ed8d39dd2f9f37">OutUnit</a>, <a href="#a4b1fff9a8fad2b78ec60ff06dfe36db9">PatchesOffsets</a>, <a href="#a689c387664c7bbe7acdf44a5bb4d47ec">shouldSkipAttribute</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#ad16686174287aeb36289484f271d5225">llvm::DWARFFormValue::skipValue</a>.</p>

</div>
</div>

### finalizeAbbreviations() {#a2fac38670ec896a95b399e4a82786291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DIEAttributeCloner::finalizeAbbreviations (bool HasChildrenToClone)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create abbreviations for the output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> after all attributes are cloned.</p>

<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>, definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-cpp">DIEAttributeCloner.cpp</a>.</p>


<p>References <a href="#a349ad92c804dcea3e5f1470bc7dc254f">AttrOutOffset</a>, <a href="#a3cffaa8f53fe7ada3bb67e3d5bd1601e">Generator</a> and <a href="#a4b1fff9a8fad2b78ec60ff06dfe36db9">PatchesOffsets</a>.</p>

</div>
</div>

### getOutOffset() {#a37d2788fbc0de7474c370f4107595b50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf_linker::parallel::DIEAttributeCloner::getOutOffset ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>Reference <a href="#a349ad92c804dcea3e5f1470bc7dc254f">AttrOutOffset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### cloneAddressAttr() {#aba2b0348c09eb9e1b9245a012aab2503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t DIEAttributeCloner::cloneAddressAttr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec">DWARFAbbreviationDeclaration::AttributeSpec</a> &amp; AttrSpec)</td>
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

<p>Clone address attribute.</p>

<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>, definition at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-cpp">DIEAttributeCloner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec/#a334610a585463d47be91041e10e9ba7a">llvm::DWARFAbbreviationDeclaration::AttributeSpec::Attr</a>, <a href="#a088d2a29666b318b459ebcbd96ee1d5c">AttrInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec/#ae1a5d450fc1291db4a1981cfbd38fc0b">llvm::DWARFAbbreviationDeclaration::AttributeSpec::Form</a>, <a href="#aa01fc91b9ebc371159da3ccad8f09f56">FuncAddressAdjustment</a>, <a href="#a3cffaa8f53fe7ada3bb67e3d5bd1601e">Generator</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#aff41df6db83444b2f49193bc1f362fae">llvm::DWARFFormValue::getRawUValue</a>, <a href="#a8ecc8aaf62d09e944d05a9c4e05e908e">InputDieEntry</a>, <a href="#a0ef0e422c431e97a439e9041c06c9caf">InUnit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ab7025b300d22532590ed8d39dd2f9f37">OutUnit</a> and <a href="#ae2c034842b86e727cabd95686828fc5d">VarAddressAdjustment</a>.</p>


<p>Referenced by <a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a>.</p>

</div>
</div>

### cloneBlockAttr() {#a00f85301e155c37fcab125f50a67cfb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t DIEAttributeCloner::cloneBlockAttr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec">DWARFAbbreviationDeclaration::AttributeSpec</a> &amp; AttrSpec)</td>
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

<p>Clone block or exprloc attribute.</p>

<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>, definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-cpp">DIEAttributeCloner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec/#a334610a585463d47be91041e10e9ba7a">llvm::DWARFAbbreviationDeclaration::AttributeSpec::Attr</a>, <a href="#a088d2a29666b318b459ebcbd96ee1d5c">AttrInfo</a>, <a href="#a349ad92c804dcea3e5f1470bc7dc254f">AttrOutOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="#a1bfcd90fb03cb9b0f0c72103391e936b">DebugInfoOutputSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a031683a2f97f9d8db3b493ada43e2228ab7f7ffb183c98435d2b766c0bd9412eb">llvm::DWARFFormValue::FC_Block</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a031683a2f97f9d8db3b493ada43e2228a5a1c5d88ff1af292b7f88f4c8a4fa8f1">llvm::DWARFFormValue::FC_Exprloc</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec/#ae1a5d450fc1291db4a1981cfbd38fc0b">llvm::DWARFAbbreviationDeclaration::AttributeSpec::Form</a>, <a href="#a3cffaa8f53fe7ada3bb67e3d5bd1601e">Generator</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a3429295ea0185a78b39c2e853b13b851">llvm::DWARFFormValue::getAsBlock</a>, <a href="#a1998c4c5f557be9d1e4b4b6d51fc437c">HasLocationExpressionAddress</a>, <a href="#a0ef0e422c431e97a439e9041c06c9caf">InUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a7f4acdd5d8a9b78623878262b10f8e4f">llvm::DWARFFormValue::isFormClass</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfattribute/#abcfbc296ea65dfc9205a4211bfb2d45b">llvm::DWARFAttribute::mayHaveLocationExpr</a>, <a href="#ab7025b300d22532590ed8d39dd2f9f37">OutUnit</a>, <a href="#a4b1fff9a8fad2b78ec60ff06dfe36db9">PatchesOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="#ae2c034842b86e727cabd95686828fc5d">VarAddressAdjustment</a>.</p>


<p>Referenced by <a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a>.</p>

</div>
</div>

### cloneDieRefAttr() {#a62035c942faa72252459166166847bff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t DIEAttributeCloner::cloneDieRefAttr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec">DWARFAbbreviationDeclaration::AttributeSpec</a> &amp; AttrSpec)</td>
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

<p>Clone attribute referencing another <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-cpp">DIEAttributeCloner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec/#a334610a585463d47be91041e10e9ba7a">llvm::DWARFAbbreviationDeclaration::AttributeSpec::Attr</a>, <a href="#a349ad92c804dcea3e5f1470bc7dc254f">AttrOutOffset</a>, <a href="#a1bfcd90fb03cb9b0f0c72103391e936b">DebugInfoOutputSection</a>, <a href="#a3cffaa8f53fe7ada3bb67e3d5bd1601e">Generator</a>, <a href="#a8ecc8aaf62d09e944d05a9c4e05e908e">InputDieEntry</a>, <a href="#abecbbd533de7c6ddd95ecb684e426d60">InputDIEIdx</a>, <a href="#a0ef0e422c431e97a439e9041c06c9caf">InUnit</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/compileunit/dieinfo/#a4fb9f942a186fdee7f8665c5d3363ee3">llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::needToPlaceInTypeTable</a>, <a href="#ae8e326dcecfa5386350eb28a2f7aef49">OutDIE</a>, <a href="#ab7025b300d22532590ed8d39dd2f9f37">OutUnit</a>, <a href="#a4b1fff9a8fad2b78ec60ff06dfe36db9">PatchesOffsets</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#afcf78d2889ce6c20ba9de57049ac479fad28670925b341cc0d43e6a0535646d38">llvm::dwarf_linker::parallel::Resolve</a>.</p>


<p>Referenced by <a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a>.</p>

</div>
</div>

### cloneScalarAttr() {#a46b9ec0a91b5f1a1ea42559b16bcdc4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t DIEAttributeCloner::cloneScalarAttr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec">DWARFAbbreviationDeclaration::AttributeSpec</a> &amp; AttrSpec)</td>
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

<p>Clone scalar attribute.</p>

<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>, definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-cpp">DIEAttributeCloner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec/#a334610a585463d47be91041e10e9ba7a">llvm::DWARFAbbreviationDeclaration::AttributeSpec::Attr</a>, <a href="#a088d2a29666b318b459ebcbd96ee1d5c">AttrInfo</a>, <a href="#a349ad92c804dcea3e5f1470bc7dc254f">AttrOutOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24aef3096c553fe7abacddd617a1c377330">llvm::dwarf_linker::DebugAddr</a>, <a href="#a1bfcd90fb03cb9b0f0c72103391e936b">DebugInfoOutputSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a64dbaf07475300f47afcfd402de0a403">llvm::dwarf_linker::DebugLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a2a7a1d32129c0c2cd671b7456920a8fd">llvm::dwarf_linker::DebugMacinfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac8a9bc90088014d33564a1f67dc6243e">llvm::dwarf_linker::DebugMacro</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24aff29b8418c7593f015431386cf40b181">llvm::dwarf_linker::DebugStrOffsets</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a92aaa66ec12298250ec99438ffd2df2c">llvm::dwarf::doesFormBelongToClass</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a031683a2f97f9d8db3b493ada43e2228ad4d4f9b4b3969ebc99a811b168072ff0">llvm::DWARFFormValue::FC_SectionOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec/#ae1a5d450fc1291db4a1981cfbd38fc0b">llvm::DWARFAbbreviationDeclaration::AttributeSpec::Form</a>, <a href="#aa01fc91b9ebc371159da3ccad8f09f56">FuncAddressAdjustment</a>, <a href="#a3cffaa8f53fe7ada3bb67e3d5bd1601e">Generator</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a34b4361a52bbe519104734f746a248f9">llvm::DWARFFormValue::getAsSectionOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a95368a5748aa1df8f1d4a2923585a3d3">llvm::DWARFFormValue::getAsSignedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#acf6d7ec7b1699c2bf60e54e032aae623">llvm::DWARFFormValue::getAsUnsignedConstant</a>, <a href="#a8ecc8aaf62d09e944d05a9c4e05e908e">InputDieEntry</a>, <a href="#abecbbd533de7c6ddd95ecb684e426d60">InputDIEIdx</a>, <a href="#a0ef0e422c431e97a439e9041c06c9caf">InUnit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a4374cf34c5d58482ffae982196bd2114">llvm::Macro</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfattribute/#a789c218461af8a727bcdfd037ee666b9">llvm::DWARFAttribute::mayHaveLocationList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#ae8e326dcecfa5386350eb28a2f7aef49">OutDIE</a>, <a href="#ab7025b300d22532590ed8d39dd2f9f37">OutUnit</a>, <a href="#a4b1fff9a8fad2b78ec60ff06dfe36db9">PatchesOffsets</a> and <a href="#ae2c034842b86e727cabd95686828fc5d">VarAddressAdjustment</a>.</p>


<p>Referenced by <a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a>.</p>

</div>
</div>

### cloneStringAttr() {#a77e10b3b8f2ee1990c6ea01fb817526c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t DIEAttributeCloner::cloneStringAttr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec">DWARFAbbreviationDeclaration::AttributeSpec</a> &amp; AttrSpec)</td>
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

<p>Clone string attribute.</p>

<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-cpp">DIEAttributeCloner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec/#a334610a585463d47be91041e10e9ba7a">llvm::DWARFAbbreviationDeclaration::AttributeSpec::Attr</a>, <a href="#a088d2a29666b318b459ebcbd96ee1d5c">AttrInfo</a>, <a href="#a349ad92c804dcea3e5f1470bc7dc254f">AttrOutOffset</a>, <a href="#a1bfcd90fb03cb9b0f0c72103391e936b">DebugInfoOutputSection</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec/#ae1a5d450fc1291db4a1981cfbd38fc0b">llvm::DWARFAbbreviationDeclaration::AttributeSpec::Form</a>, <a href="#a3cffaa8f53fe7ada3bb67e3d5bd1601e">Generator</a>, <a href="#abecbbd533de7c6ddd95ecb684e426d60">InputDIEIdx</a>, <a href="#a0ef0e422c431e97a439e9041c06c9caf">InUnit</a>, <a href="#ae8e326dcecfa5386350eb28a2f7aef49">OutDIE</a>, <a href="#ab7025b300d22532590ed8d39dd2f9f37">OutUnit</a>, <a href="#a4b1fff9a8fad2b78ec60ff06dfe36db9">PatchesOffsets</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a39a67e6dc97585d609932dc2fb04a377">llvm::dwarf::toString</a> and <a href="#aeb840d515852065f5697378af677962a">Use_DW_FORM_strp</a>.</p>


<p>Referenced by <a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a>.</p>

</div>
</div>

### shouldSkipAttribute() {#a689c387664c7bbe7acdf44a5bb4d47ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DIEAttributeCloner::shouldSkipAttribute (<a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec">DWARFAbbreviationDeclaration::AttributeSpec</a> AttrSpec)</td>
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

<p>Returns true if attribute should be skipped.</p>

<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-cpp">DIEAttributeCloner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec/#a334610a585463d47be91041e10e9ba7a">llvm::DWARFAbbreviationDeclaration::AttributeSpec::Attr</a>, <a href="#aa01fc91b9ebc371159da3ccad8f09f56">FuncAddressAdjustment</a>, <a href="#a1998c4c5f557be9d1e4b4b6d51fc437c">HasLocationExpressionAddress</a>, <a href="#abecbbd533de7c6ddd95ecb684e426d60">InputDIEIdx</a>, <a href="#a0ef0e422c431e97a439e9041c06c9caf">InUnit</a> and <a href="#ae2c034842b86e727cabd95686828fc5d">VarAddressAdjustment</a>.</p>


<p>Referenced by <a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AttrInfo {#a088d2a29666b318b459ebcbd96ee1d5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributesInfo llvm::dwarf_linker::parallel::DIEAttributeCloner::AttrInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cannot be used concurrently.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>Referenced by <a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a>, <a href="#aba2b0348c09eb9e1b9245a012aab2503">cloneAddressAttr</a>, <a href="#a00f85301e155c37fcab125f50a67cfb4">cloneBlockAttr</a>, <a href="#a46b9ec0a91b5f1a1ea42559b16bcdc4d">cloneScalarAttr</a> and <a href="#a77e10b3b8f2ee1990c6ea01fb817526c">cloneStringAttr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AttrOutOffset {#a349ad92c804dcea3e5f1470bc7dc254f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf_linker::parallel::DIEAttributeCloner::AttrOutOffset = 0</td>
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

<p>Output offset after all attributes.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>Referenced by <a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a>, <a href="#a00f85301e155c37fcab125f50a67cfb4">cloneBlockAttr</a>, <a href="#a62035c942faa72252459166166847bff">cloneDieRefAttr</a>, <a href="#a46b9ec0a91b5f1a1ea42559b16bcdc4d">cloneScalarAttr</a>, <a href="#a77e10b3b8f2ee1990c6ea01fb817526c">cloneStringAttr</a>, <a href="#a2fac38670ec896a95b399e4a82786291">finalizeAbbreviations</a> and <a href="#a37d2788fbc0de7474c370f4107595b50">getOutOffset</a>.</p>

</div>
</div>

### DebugInfoOutputSection {#a1bfcd90fb03cb9b0f0c72103391e936b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionDescriptor&amp; llvm::dwarf_linker::parallel::DIEAttributeCloner::DebugInfoOutputSection</td>
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

<p>.debug_info section descriptor.</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>Referenced by <a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a>, <a href="#a00f85301e155c37fcab125f50a67cfb4">cloneBlockAttr</a>, <a href="#a62035c942faa72252459166166847bff">cloneDieRefAttr</a>, <a href="#a46b9ec0a91b5f1a1ea42559b16bcdc4d">cloneScalarAttr</a>, <a href="#a77e10b3b8f2ee1990c6ea01fb817526c">cloneStringAttr</a> and <a href="#a80a2ac72206c04fe2cb7714b513b95dd">DIEAttributeCloner</a>.</p>

</div>
</div>

### FuncAddressAdjustment {#aa01fc91b9ebc371159da3ccad8f09f56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;int64_t&gt; llvm::dwarf_linker::parallel::DIEAttributeCloner::FuncAddressAdjustment</td>
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

<p>Relocation adjustment for the function address ranges.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>Referenced by <a href="#aba2b0348c09eb9e1b9245a012aab2503">cloneAddressAttr</a>, <a href="#a46b9ec0a91b5f1a1ea42559b16bcdc4d">cloneScalarAttr</a>, <a href="#a66eb90e2a122d1694832a1718a6e3510">DIEAttributeCloner</a>, <a href="#a80a2ac72206c04fe2cb7714b513b95dd">DIEAttributeCloner</a>, <a href="#af97b9a61c488c6624b087784fe2a5122">DIEAttributeCloner</a> and <a href="#a689c387664c7bbe7acdf44a5bb4d47ec">shouldSkipAttribute</a>.</p>

</div>
</div>

### Generator {#a3cffaa8f53fe7ada3bb67e3d5bd1601e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIEGenerator&amp; llvm::dwarf_linker::parallel::DIEAttributeCloner::Generator</td>
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

<p>Output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> generator.</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>Referenced by <a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a>, <a href="#aba2b0348c09eb9e1b9245a012aab2503">cloneAddressAttr</a>, <a href="#a00f85301e155c37fcab125f50a67cfb4">cloneBlockAttr</a>, <a href="#a62035c942faa72252459166166847bff">cloneDieRefAttr</a>, <a href="#a46b9ec0a91b5f1a1ea42559b16bcdc4d">cloneScalarAttr</a>, <a href="#a77e10b3b8f2ee1990c6ea01fb817526c">cloneStringAttr</a>, <a href="#a66eb90e2a122d1694832a1718a6e3510">DIEAttributeCloner</a>, <a href="#a80a2ac72206c04fe2cb7714b513b95dd">DIEAttributeCloner</a>, <a href="#af97b9a61c488c6624b087784fe2a5122">DIEAttributeCloner</a> and <a href="#a2fac38670ec896a95b399e4a82786291">finalizeAbbreviations</a>.</p>

</div>
</div>

### HasLocationExpressionAddress {#a1998c4c5f557be9d1e4b4b6d51fc437c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DIEAttributeCloner::HasLocationExpressionAddress = false</td>
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

<p>Indicates whether InputDieEntry has an location attribute containg address expression.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>Referenced by <a href="#a00f85301e155c37fcab125f50a67cfb4">cloneBlockAttr</a>, <a href="#a66eb90e2a122d1694832a1718a6e3510">DIEAttributeCloner</a>, <a href="#a80a2ac72206c04fe2cb7714b513b95dd">DIEAttributeCloner</a>, <a href="#af97b9a61c488c6624b087784fe2a5122">DIEAttributeCloner</a> and <a href="#a689c387664c7bbe7acdf44a5bb4d47ec">shouldSkipAttribute</a>.</p>

</div>
</div>

### InputDieEntry {#a8ecc8aaf62d09e944d05a9c4e05e908e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry* llvm::dwarf_linker::parallel::DIEAttributeCloner::InputDieEntry = nullptr</td>
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

<p><a href="/web-llvm/docs/api/classes/input">Input</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> entry.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>Referenced by <a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a>, <a href="#aba2b0348c09eb9e1b9245a012aab2503">cloneAddressAttr</a>, <a href="#a62035c942faa72252459166166847bff">cloneDieRefAttr</a>, <a href="#a46b9ec0a91b5f1a1ea42559b16bcdc4d">cloneScalarAttr</a>, <a href="#a66eb90e2a122d1694832a1718a6e3510">DIEAttributeCloner</a>, <a href="#a80a2ac72206c04fe2cb7714b513b95dd">DIEAttributeCloner</a> and <a href="#af97b9a61c488c6624b087784fe2a5122">DIEAttributeCloner</a>.</p>

</div>
</div>

### InputDIEIdx {#abecbbd533de7c6ddd95ecb684e426d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dwarf_linker::parallel::DIEAttributeCloner::InputDIEIdx = 0</td>
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

<p><a href="/web-llvm/docs/api/classes/input">Input</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> index.</p>

<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>Referenced by <a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a>, <a href="#a62035c942faa72252459166166847bff">cloneDieRefAttr</a>, <a href="#a46b9ec0a91b5f1a1ea42559b16bcdc4d">cloneScalarAttr</a>, <a href="#a77e10b3b8f2ee1990c6ea01fb817526c">cloneStringAttr</a>, <a href="#a80a2ac72206c04fe2cb7714b513b95dd">DIEAttributeCloner</a> and <a href="#a689c387664c7bbe7acdf44a5bb4d47ec">shouldSkipAttribute</a>.</p>

</div>
</div>

### InUnit {#a0ef0e422c431e97a439e9041c06c9caf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit&amp; llvm::dwarf_linker::parallel::DIEAttributeCloner::InUnit</td>
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

<p><a href="/web-llvm/docs/api/classes/input">Input</a> compilation unit.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>Referenced by <a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a>, <a href="#aba2b0348c09eb9e1b9245a012aab2503">cloneAddressAttr</a>, <a href="#a00f85301e155c37fcab125f50a67cfb4">cloneBlockAttr</a>, <a href="#a62035c942faa72252459166166847bff">cloneDieRefAttr</a>, <a href="#a46b9ec0a91b5f1a1ea42559b16bcdc4d">cloneScalarAttr</a>, <a href="#a77e10b3b8f2ee1990c6ea01fb817526c">cloneStringAttr</a>, <a href="#a66eb90e2a122d1694832a1718a6e3510">DIEAttributeCloner</a>, <a href="#a80a2ac72206c04fe2cb7714b513b95dd">DIEAttributeCloner</a>, <a href="#af97b9a61c488c6624b087784fe2a5122">DIEAttributeCloner</a> and <a href="#a689c387664c7bbe7acdf44a5bb4d47ec">shouldSkipAttribute</a>.</p>

</div>
</div>

### OutDIE {#ae8e326dcecfa5386350eb28a2f7aef49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE* llvm::dwarf_linker::parallel::DIEAttributeCloner::OutDIE = nullptr</td>
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

<p>Output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>Referenced by <a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a>, <a href="#a62035c942faa72252459166166847bff">cloneDieRefAttr</a>, <a href="#a46b9ec0a91b5f1a1ea42559b16bcdc4d">cloneScalarAttr</a>, <a href="#a77e10b3b8f2ee1990c6ea01fb817526c">cloneStringAttr</a>, <a href="#a66eb90e2a122d1694832a1718a6e3510">DIEAttributeCloner</a>, <a href="#a80a2ac72206c04fe2cb7714b513b95dd">DIEAttributeCloner</a> and <a href="#af97b9a61c488c6624b087784fe2a5122">DIEAttributeCloner</a>.</p>

</div>
</div>

### OutUnit {#ab7025b300d22532590ed8d39dd2f9f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit::OutputUnitVariantPtr llvm::dwarf_linker::parallel::DIEAttributeCloner::OutUnit</td>
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

<p>Output unit(either "plain" compilation unit, either artificial type unit).</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>Referenced by <a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a>, <a href="#aba2b0348c09eb9e1b9245a012aab2503">cloneAddressAttr</a>, <a href="#a00f85301e155c37fcab125f50a67cfb4">cloneBlockAttr</a>, <a href="#a62035c942faa72252459166166847bff">cloneDieRefAttr</a>, <a href="#a46b9ec0a91b5f1a1ea42559b16bcdc4d">cloneScalarAttr</a>, <a href="#a77e10b3b8f2ee1990c6ea01fb817526c">cloneStringAttr</a>, <a href="#a66eb90e2a122d1694832a1718a6e3510">DIEAttributeCloner</a>, <a href="#a80a2ac72206c04fe2cb7714b513b95dd">DIEAttributeCloner</a> and <a href="#af97b9a61c488c6624b087784fe2a5122">DIEAttributeCloner</a>.</p>

</div>
</div>

### PatchesOffsets {#a4b1fff9a8fad2b78ec60ff06dfe36db9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetsPtrVector llvm::dwarf_linker::parallel::DIEAttributeCloner::PatchesOffsets</td>
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

<p>Patches for the cloned attributes.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>Referenced by <a href="#a601419af5c3f8b56909c01a8596aecb7">clone</a>, <a href="#a00f85301e155c37fcab125f50a67cfb4">cloneBlockAttr</a>, <a href="#a62035c942faa72252459166166847bff">cloneDieRefAttr</a>, <a href="#a46b9ec0a91b5f1a1ea42559b16bcdc4d">cloneScalarAttr</a>, <a href="#a77e10b3b8f2ee1990c6ea01fb817526c">cloneStringAttr</a> and <a href="#a2fac38670ec896a95b399e4a82786291">finalizeAbbreviations</a>.</p>

</div>
</div>

### Use\_DW\_FORM\_strp {#aeb840d515852065f5697378af677962a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DIEAttributeCloner::Use_DW_FORM_strp = false</td>
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

<p>This flag forces using DW_FORM_strp for string attributes.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>Referenced by <a href="#a77e10b3b8f2ee1990c6ea01fb817526c">cloneStringAttr</a> and <a href="#a80a2ac72206c04fe2cb7714b513b95dd">DIEAttributeCloner</a>.</p>

</div>
</div>

### VarAddressAdjustment {#ae2c034842b86e727cabd95686828fc5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;int64_t&gt; llvm::dwarf_linker::parallel::DIEAttributeCloner::VarAddressAdjustment</td>
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

<p>Relocation adjustment for the variable locations.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a>.</p>


<p>Referenced by <a href="#aba2b0348c09eb9e1b9245a012aab2503">cloneAddressAttr</a>, <a href="#a00f85301e155c37fcab125f50a67cfb4">cloneBlockAttr</a>, <a href="#a46b9ec0a91b5f1a1ea42559b16bcdc4d">cloneScalarAttr</a>, <a href="#a66eb90e2a122d1694832a1718a6e3510">DIEAttributeCloner</a>, <a href="#a80a2ac72206c04fe2cb7714b513b95dd">DIEAttributeCloner</a>, <a href="#af97b9a61c488c6624b087784fe2a5122">DIEAttributeCloner</a> and <a href="#a689c387664c7bbe7acdf44a5bb4d47ec">shouldSkipAttribute</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-cpp">DIEAttributeCloner.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dieattributecloner-h">DIEAttributeCloner.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
